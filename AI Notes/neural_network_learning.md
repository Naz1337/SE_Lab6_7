# Machine Learning (Artificial Neural Network) (Part 2)

## Module 3.2: BCS2313 Artificial Intelligence Techniques

### What You'll Learn
- Backpropagation Learning

### Neural Network Application Development
1. Methodology
2. Data collection
3. Data normalization
4. Neural network design
5. Neural network training
6. Testing

### Data Collection
- Data collection involves gathering chosen data to be used as a training sample.

#### Sample Data
| Sepal Length | Sepal Width | Petal Length | Petal Width | Iris Class     |
|--------------|-------------|--------------|-------------|----------------|
| 5.7          | 4.4         | 1.5          | 0.4         | Iris-setosa    |
| 5.4          | 3.9         | 1.3          | 0.4         | Iris-setosa    |
| 6.1          | 2.8         | 4.7          | 1.2         | Iris-versicolor|
| 6.4          | 2.9         | 4.3          | 1.3         | Iris-versicolor|
| 6.1          | 3.0         | 144.9        | 1.8         | Iris-virginica |
| 6.4          | 2.8         | 5.6          | 2.1         | Iris-virginica |

#### Attribute Ranges
| Attribute    | Minimum | Maximum |
|--------------|---------|---------|
| Sepal length | 4.3     | 7.9     |
| Sepal width  | 2.0     | 4.4     |
| Petal length | 1.0     | 6.9     |
| Petal width  | 0.1     | 2.5     |

### Data Normalization
- Data normalization process is applied to the selected data.
- Max-Min normalization formula is used.

### Neural Network Design
- 4 input attributes and 1 decision
- 4 input nodes and 1 output node

### Forward Propagation
1. Neuron Activation
2. Neuron Transfer
3. Forward Propagation

#### Neuron Activation
- Calculated as the weighted sum of the inputs: `activation = sum(weight_i * input_i) + bias`

#### Neuron Transfer
- Transfer functions: Sigmoid, Tanh, Rectifier

### Neural Network Training
- Back-propagation training is used to train the networks.

### Backpropagation
1. Transfer Derivative
2. Error Backpropagation

#### Transfer Derivative
- Derivative of the sigmoid transfer function: `derivative = output * (1.0 - output)`

#### Error Backpropagation
- Error for each output neuron: `error = (expected - output) * transfer_derivative(output)`

### Train Network
- The network is trained using stochastic gradient descent.

### Update Weights
- Weights are updated with delta weight changes: `weight = weight + learning_rate * error * input`
