# Question 1

> Identify THREE type of software environment that significant to the online groceries ordering system development and describe each of them based-on software environment differentiate factors.

Based on the given project scenario, the following three software environments are highly relevant:

1. **Local Environment:** 

    The local environment is typically where developers initially build and test the software. It's often their individual computer systems where they write and debug their code before it gets pushed into the shared project repository. In the context of the grocery ordering system, developers might create modules for user registration, groceries ordering, rider and supplier registration, and payments authorization on their local machines. They can also make changes and solve issues in this environment without the risk of disrupting the project as a whole.

2. **Integration Environment:**

    The integration environment is where the different components of the software developed by various developers are combined and tested for interoperability. In the context of the grocery ordering system, after the individual components have been developed and tested in the local environment, they would be merged in the integration environment. Here, the modules for ordering, payment, and registration would be tested together to ensure they work seamlessly as a complete system. This is where issues that emerge from the interaction of different modules will be discovered and resolved.

3. **Testing Environment:**

    The testing environment is an environment that replicates the production environment as closely as possible where the complete software is thoroughly tested. This environment is crucial to ensure the stability, security, and functionality of the software before it goes live. For the grocery ordering system, it's in this environment that rigorous testing would be conducted, including user acceptance testing (UAT), stress testing, and security testing. The system would be tested to handle groceries ordering, payments, delivery tracking, and report generation. 

Remember that these environments serve different purposes, and it's important to maintain a separation between them to reduce the risk of errors and ensure a high quality final product. The client's desire for frequent progress updates would be best met by demonstrating the system's capabilities in these environments as the project progresses.

---

# Question 2

> Based on the given case study, identify and describe THREE (3) potential tools that you might used to develop the online groceries ordering system.

Based on the given case study, and the provided list of valid tools from your class note, here are three potential tools that you might use to develop the online groceries ordering system:

1. **Integrated Development Environment (IDE):** This is a software application that provides comprehensive facilities to computer programmers for software development. An IDE typically includes a source code editor, build automation tools, and a debugger. In the context of this project, an IDE could be crucial for effective and efficient software development. IDEs such as Visual Studio Code or IntelliJ IDEA provide robust features that aid in writing, testing, and debugging code. They provide features like code completion, syntax highlighting, and built-in terminal, all of which would be useful in this project. 

2. **Version Control:** Version control systems are a category of software tools that help a software team manage changes to source code over time. They keep track of every modification to the code in a special kind of database, so if a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members. In this project, a version control system like Git could be used to handle the source code's versions, track changes, and allow for smooth collaboration among developers. The client's requirement for frequent updates and detailed progress reports could also be facilitated by maintaining transparent and accessible logs of changes through version control.

3. **Tools for testing by simulation:** Given that the end-users are known to be computer illiterate and manage their work manually in practice, it's vital to ensure that the software works as expected before deploying it. Simulation tools can provide an effective way to test the software without the risks or costs associated with testing in a live environment. These tools create a virtual environment that mimics the intended environment in which the software application will run. This will allow your team to catch and address any potential bugs or issues that could impact the performance or usability of the application. Tools like Selenium (for web application testing) could be used for this purpose. 

It's important to note that while these tools can be invaluable for developing the software, the success of the project will also depend on factors like the team's ability to effectively communicate and collaborate, the clear understanding and definition of the project requirements, and an agile and iterative approach to development.

---

# Question 3

> Based on the given case study, compare THREE (3) advantages and THREE (3) disadvantages of open source tools and proprietery tools in developing the inventory system.

Sure, here's a comparison of advantages and disadvantages for open source and proprietary tools when developing the inventory system.

```html
<table>
  <tr>
    <th></th>
    <th>Open Source Tools</th>
    <th>Proprietary Tools</th>
  </tr>
  <tr>
    <th>Advantages</th>
    <td>
      <ul>
        <li>Customizability: Open source tools are flexible and customizable to fit specific needs of the project.</li>
        <li>Cost Efficiency: Usually free or low cost, which is important given the budget is released only once basic functions are ready.</li>
        <li>Community Support: Large support communities exist to help solve issues or provide guidance.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Professional Support: Support is usually available through the vendor, including documentation, user manuals, and direct support.</li>
        <li>Ready-made Features: Proprietary tools often come with built-in features that can expedite the development process.</li>
        <li>Reliability: Regular updates and maintenance, with a focus on stability and reliability.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Disadvantages</th>
    <td>
      <ul>
        <li>Support: While there's community support, there may not be dedicated customer service in case of issues.</li>
        <li>Complexity: Open source tools often require more technical expertise to customize and implement effectively.</li>
        <li>Compatibility Issues: May face compatibility issues with other software, systems, or platforms.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Cost: Proprietary tools often require purchase or subscription fees, which may be high.</li>
        <li>Customizability: They are usually less flexible and customizable than open source tools.</li>
        <li>Vendor Lock-in: There's the risk of becoming dependent on the vendor for updates and support.</li>
      </ul>
    </td>
  </tr>
</table>
```

This will be displayed as:

|       | Open Source Tools                                                                                                              | Proprietary Tools                                                                                |
|-------|--------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Advantages | - Customizability: Open source tools are flexible and customizable to fit specific needs of the project. <br> - Cost Efficiency: Usually free or low cost, which is important given the budget is released only once basic functions are ready. <br> - Community Support: Large support communities exist to help solve issues or provide guidance.             | - Professional Support: Support is usually available through the vendor, including documentation, user manuals, and direct support. <br> - Ready-made Features: Proprietary tools often come with built-in features that can expedite the development process. <br> - Reliability: Regular updates and maintenance, with a focus on stability and reliability.             |
| Disadvantages | - Support: While there's community support, there may not be dedicated customer service in case of issues. <br> - Complexity: Open source tools often require more technical expertise to customize and implement effectively. <br> - Compatibility Issues: May face compatibility issues with other software, systems, or platforms. | - Cost: Proprietary tools often require purchase or subscription fees, which may be high. <br> - Customizability: They are usually less flexible and customizable than open source tools. <br> - Vendor Lock-in: There's the risk of becoming dependent on the vendor for updates and support. |

### html stuff
<table>
  <tr>
    <th></th>
    <th>Open Source Tools</th>
    <th>Proprietary Tools</th>
  </tr>
  <tr>
    <th>Advantages</th>
    <td>
      <ul>
        <li>Customizability: Open source tools are flexible and customizable to fit specific needs of the project.</li>
        <li>Cost Efficiency: Usually free or low cost, which is important given the budget is released only once basic functions are ready.</li>
        <li>Community Support: Large support communities exist to help solve issues or provide guidance.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Professional Support: Support is usually available through the vendor, including documentation, user manuals, and direct support.</li>
        <li>Ready-made Features: Proprietary tools often come with built-in features that can expedite the development process.</li>
        <li>Reliability: Regular updates and maintenance, with a focus on stability and reliability.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Disadvantages</th>
    <td>
      <ul>
        <li>Support: While there's community support, there may not be dedicated customer service in case of issues.</li>
        <li>Complexity: Open source tools often require more technical expertise to customize and implement effectively.</li>
        <li>Compatibility Issues: May face compatibility issues with other software, systems, or platforms.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Cost: Proprietary tools often require purchase or subscription fees, which may be high.</li>
        <li>Customizability: They are usually less flexible and customizable than open source tools.</li>
        <li>Vendor Lock-in: There's the risk of becoming dependent on the vendor for updates and support.</li>
      </ul>
    </td>
  </tr>
</table>

---

# Question 4

> Compare how to create PRIVATE vs PUBLIC API value chain based on the FOUR (4) basic elements of API value chain

Creating both private and public APIs involves the same basic elements of the API value chain, which are business assets, API provider, developers, and applications. However, the way these elements are managed varies depending on whether the API is private or public.

For the LYYC web-based grocery system, let's discuss how the four basic elements of API value chain could be created differently for a private API and a public API.

**Private API Value Chain:**

1. **Business Assets:** The business assets for a private API include the LYYC's data and functionalities such as the ordering system, rider and supplier registration, payment processing, delivery tracking, and report generation. As these assets are sensitive and proprietary, they should only be accessed within the LYYC organization or by specific authorized parties.

2. **API Provider:** In this scenario, the API provider is likely the LYYC organization or a specific IT team within the organization. The provider would ensure secure access and use of the business assets via the private API, restricting access to specific in-house developers or trusted partners.

3. **Developers:** Developers would likely be LYYC employees or closely allied third-party developers. Their job is to use the private API to create web-based applications that manage the online grocery ordering system.

4. **Applications:** Applications created from the private API would include functionalities like ordering, registration, payment, delivery tracking, and report generation. These applications would be used internally by LYYC, partners, or specific end-users such as the system owner, rider, supplier, and customers.

**Public API Value Chain:**

1. **Business Assets:** If LYYC decides to create a public API, it would have to decide which business assets to expose. It might include less sensitive data or functionalities that could be used by external developers to create applications beneficial to LYYC, like creating an API for tracking deliveries which can be used by third-party apps to improve customer experience.

2. **API Provider:** As the provider of the public API, LYYC would need to promote the API to external developers and incentivize its use. They may need to provide documentation, support, and potentially even monetary incentives.

3. **Developers:** Developers for public APIs are generally not employees of the organization. They could be independent developers or developers from other companies. Their motivations to use the API can range from interest in technology, the challenge of innovating, or the potential to earn money.

4. **Applications:** Applications created from a public API could reach a wider audience. The LYYC would need to create or utilize existing distribution channels (like app stores or a section on their own website) to promote these applications to the end-users.

In summary, private APIs and public APIs share the same basic elements of the value chain but differ in how these elements are managed and utilized, with private APIs being more restrictive and targeted towards internal use and public APIs being more open and targeted towards external use.
