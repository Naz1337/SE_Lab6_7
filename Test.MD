# Graph Definition and Terminologies

## Definition of a Graph

A **Graph** in the context of discrete structures and applications is an important mathematical structure used to model relationships between objects. It is denoted as G and consists of:

- **V** – a nonempty set of vertices (or nodes) represented by points. 
  - If the vertex set is infinite, we have an Infinite graph. 
  - If the vertex set is finite, we have a Finite graph.
- **E** – a set of Edges represented by line segments or curves. Each edge has either one or two vertices associated with it, called its endpoints. An edge is said to connect its endpoints. 

In mathematical notation, a Graph G is represented as:

    G = (V, E)

The way of drawing a graph is arbitrary as long as the correct connections between vertices are depicted. The edges of the graph should not cross each other.

## Graph Terminologies

1. **Adjacent**: Two vertices are said to be adjacent if they are connected by an edge.
2. **Incident**: An edge is said to be incident to a vertex if the vertex is one of the endpoints of the edge.
3. **Degree**: The degree of a vertex in a graph is the number of edges incident with it.
4. **Isolated**: A vertex is said to be isolated if it is not an endpoint of any edge.
5. **Pendant**: A pendant vertex in a graph is a vertex that has degree 1.
6. **Initial Vertex**: In a directed graph, the initial vertex of an edge is the vertex that the edge comes from.
7. **Terminal**: In a directed graph, the terminal vertex of an edge is the vertex that the edge leads to.
8. **In-degree/Out-degree**: In a directed graph, the in-degree of a vertex is the number of edges leading into it, and the out-degree of a vertex is the number of edges leading out of it.
9. **Bipartite**: A graph is bipartite if the vertices can be divided into two disjoint sets such that every edge connects a vertex in one set to a vertex in the other set.
10. **Subgraph**: A subgraph of a graph is a graph whose vertices and edges are all from the original graph.
   
# Representing Graph and Graph Isomorphism

## Graph Representation
Graphs can be represented in three primary ways:

1. **Adjacency List**: This representation uses a list to specify the vertices that are adjacent to each vertex of the graph.

2. **Adjacency Matrix**: This represents a graph by a matrix based on the adjacency of vertices. Each cell of the matrix indicates whether an edge exists between the vertices.

3. **Incidence Matrix**: This represents a graph by a matrix based on the incidence of vertices and edges. The matrix has a row for each vertex and a column for each edge.

## Graph Isomorphism

Two simple graphs $G1 = (V1, E1)$ and $G2 = (V2, E2)$ are said to be **isomorphic** if there is a one-to-one and onto function (bijection) `f` from $V1$ to $V2$ such that for any two vertices `a` and `b` in $V1$, `a` and `b` are adjacent in $G1$ if and only if `f(a)` and `f(b)` are adjacent in $G2$.

This isomorphism preserves the adjacency relationship between vertices, creating a one-to-one correspondence that maintains this relationship.

## Conditions for Isomorphism
For two simple graphs $G1 = (V1, E1)$ and $G2 = (V2, E2)$ to be isomorphic, the following conditions must be satisfied:

1. The number of vertices in both graphs should be equal, i.e., $|V1| = |V2|$.

2. The number of edges in both graphs should be equal, i.e., $|E1| = |E2|$.

3. The corresponding vertices in $G1$ and $G2$ will have the same degree.

4. A bijection `f: V1 ➔ V2` should preserve the adjacency relationship:
    - If `{a, b}` is an edge in $E1$ then `{f(a),f(b)}` must be an edge in $E2$.
    - If `{f(a), f(b)}` is an edge in $E2$ then `{a, b}` must be an edge in $E1$.

5. The adjacency matrix of $G1$ should be the same as the adjacency matrix of $G2$, with rows and columns labeled by the images of corresponding vertices in $G1$.

There are `n!` possible one-to-one correspondences between the vertex sets of two simple graphs with `n` vertices.

# Graph Connectivity

```mermaid
graph TD;
  A --> B;
  B --> C;
  A --> C;
  D --> E;
  C --> D;
  C --> F;
  E --> F;
```
1. **Connectivity:** A graph is connected if there's a path between every pair of vertices. In the above graph, each vertex is reachable from any other vertex.
   - In formal terms, a graph $G$ is **connected** if, for every pair of vertices $v$, $w$ in $G$, there exists a path from $v$ to $w$.
2. **Disconnected Graphs:** A graph is disconnected if there are two vertices that cannot be connected by a path.
   - In formal terms, if there exists a pair of vertices $v$, $w$ in $G$ such that no path can be found from $v$ to $w$, then $G$ is **disconnected**.
3. **Degree of a Vertex:** The degree of a vertex is the number of edges incident on it. For instance, in the given graph, vertex 'C' has a degree of 4.
   - In formal terms, if a vertex $v$ in $G$ is incident with $k$ edges, then we say $v$ has a **degree** of $k$ (denoted $d(v) = k$).

Applications of graph connectivity span across various fields, including network design, transportation, and routing. Understanding graph structure and robustness is critical in these areas.

_Note: The graph provided above is undirected. In directed graphs, we differentiate between 'connectivity' and 'strong connectivity'._

---

Let's think step by step.

To solve this, we need to create a rooted tree based on the clues given. Mermaid diagram syntax uses code blocks to describe diagrams, including nodes (the vertices), their relationships (edges), and their levels (the hierarchical depth of each node). In the mermaid diagram syntax, nodes are represented by their IDs, and parent-child relationships are depicted by arrows (-->).

From the clues given:

1. Vertex z is at level 0 (root), and its children are y, f, and g.
2. Vertices h, i, and j are siblings at level 2. But we don't yet know who their parent is.
3. Vertices d and e are at level 3. We also don't know their parent.
4. The ancestors of e are x, y, and z. So, z --> y --> x --> e should be part of our tree.
5. The descendants of y are x, d, and e. We already knew y --> x --> e from the previous clue, and now we know that y --> x --> d as well.
6. The leaves are d, e, f, i, k, l, and m. We knew about d, e, and f already, and now we know there are others.
7. l and m are siblings. We don't know their parent yet.
8. The internal vertices are z, y, x, g, h, and j. We have placed all of them except h and j.

Using these clues, we can start building the tree. First, we add the root and its immediate descendants:

```mermaid
graph TB
    z-->y
    z-->f
    z-->g
```

Next, we add y's descendants:

```mermaid
graph TB
    z-->y
    z-->f
    z-->g
    y-->x
    x-->d
    x-->e
```

Since the leaves are d, e, f, i, k, l, and m, and f is already a child of z, we need to add i, k, l, and m to the tree. As h, i, j are siblings at level 2, they must be children of g. We also know l and m are siblings but we don't know their parent. Since we have no other internal vertices left, l and m must be children of i:

```mermaid
graph TB
    z-->y
    z-->f
    z-->g
    y-->x
    x-->d
    x-->e
    g-->h
    g-->i
    g-->j
    i-->l
    i-->m
```

And finally, we don't have any information about k, but since it's a leaf and all internal vertices have been used, k must be another child of i:

```mermaid
graph TB
    z-->y
    z-->f
    z-->g
    y-->x
    x-->d
    x-->e
    g-->h
    g-->i
    g-->j
    i-->l
    i-->m
    i-->k
```

This tree satisfies all the given criteria.
