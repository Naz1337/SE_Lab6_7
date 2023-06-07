# Question 1

Based on the class notes provided and the specifics of the case study, four key maintenance cost factors for the online grocery system project can be identified as follows:

1. **Team Stability**: Maintaining team stability is essential as the continuity provided by a stable team can reduce costs associated with the learning curve and knowledge transfer. In our case study, if the team that develops the online grocery system stays involved in the maintenance phase, they would have a better understanding of the system, its design decisions, and nuances, thus potentially reducing maintenance time and costs. 

2. **Staff Skills**: Since the project involves the development of an online grocery system with e-wallet payment capabilities, it is critical to have skilled staff who are familiar with e-commerce systems, e-wallet integrations, and the complexities involved. If the maintenance team lacks these skills, the company might face higher costs due to longer issue resolution times, possible system downtimes, and the potential need for external consultancy or additional training.

3. **Program Age and Structure**: As the software ages and undergoes multiple changes, the system structure may degrade, making it harder to understand, maintain, and modify. Considering the project's time constraint (6 months), it's important that the software is designed and structured well from the onset to reduce future maintenance costs. Effective documentation and usage of modern, maintainable technologies can mitigate this issue.

4. **Contractual Responsibility**: If the contract with the client doesn't include maintenance or doesn't provide incentives for future-proof design, it may lead to higher maintenance costs down the line. In the context of the online grocery system, which must support various e-wallets and serve users in a specific geographical area, it's necessary to have a design that is easily adaptable for future changes or additions (like adding support for new e-wallets or expanding to new areas).

By addressing these factors proactively, the company can optimize maintenance costs while ensuring the quality and longevity of the online grocery system.

# Question 2

REENGINEERING:

Definition:
Reengineering is the process that takes place after a system has been maintained for a significant duration, particularly when the maintenance costs are escalating. The procedure involves the use of automated tools to process and reengineer a legacy system to create a new one that's easier to maintain. Reengineering often includes restructuring or rewriting part or all of a legacy system without changing its functionality, aiming to make it easier to understand, change, and maintain.

Example from the case study:
In the provided case study, a possible example of reengineering would be if the client's existing grocery system is outdated, hard to maintain, and incurring high costs. Reengineering may be required to convert the system into a new, user-friendly online platform. This could involve redeveloping the system to support multiple e-wallet payment options prevalent in Malaysia, or re-structuring the shipping management module to be more efficient and easier to use by both the delivery staff and the customers, especially considering that many users are illiterate.

REFACTORING:

Definition:
Refactoring is a continuous process of improving a system throughout its development and evolution process. It is designed to prevent the structure and code degradation that would increase the costs and difficulties of maintaining the system. Refactoring involves modifying a program to enhance its structure, reduce its complexity, and make it easier to understand without altering its functionality. It can be thought of as 'preventative maintenance' that mitigates future change issues.

Example from the case study:
In the context of the case study, an example of refactoring could be improving the usability of the proposed online grocery system. Given that many potential users are illiterate, the developers could refactor the system to enhance the simplicity and intuitiveness of the user interface. This might involve streamlining the checkout process or using more visual cues and less text in the user interface. Moreover, considering the variety of e-wallets to be supported, the payment module might need to be refactored to maintain a simple and unified payment interface while adding support for various payment methods.

# Question 3

A legacy system, in the context of computing, refers to an old or outdated system, technology, or application that continues to be used by an organization. This could be a computer system, programming language, software application, process, or any technology that is not supported or widely available anymore but still plays a crucial role in the organization's operations.

While the term "legacy" often carries a negative connotation due to associations with obsolescence and inflexibility, these systems can also provide unique value to organizations, often having been customized over years to suit specific business needs. However, these systems can be challenging to maintain, enhance, or integrate with more modern systems and technologies, and often pose increased security risks.

Six possible legacy system components include:

1. **Hardware:** This includes physical servers, computers, data storage systems, networking equipment, and peripherals that are no longer in production or support.

2. **Operating Systems:** The foundational software that runs on the hardware could be out-of-date, such as older versions of Windows Server, UNIX, or Linux distributions that no longer receive security updates or patches.

3. **Software Applications:** Specific applications or software suites that are integral to business operations but are out of date or unsupported fall into this category. These could be industry-specific tools, bespoke software developed in-house, or older versions of commonly used applications.

4. **Programming Languages and Libraries:** The application software might have been written in older programming languages that are no longer in wide use, or it might depend on libraries or frameworks that are not supported anymore.

5. **Databases:** Legacy systems may utilize outdated database technologies that are no longer supported or have been surpassed by more efficient, secure, and robust solutions.

6. **Business Processes:** Legacy systems can be closely tied to specific business processes that have been in place for many years. These may be inefficient compared to more modern processes but are retained due to the cost or difficulty of change.

For your specific case of building an online grocery system, you will need to consider these components, specifically focusing on aspects that facilitate user-friendliness (since many users are illiterate), support for various e-wallets in Malaysia (which involves integrating with these external systems), and robust shipping management capabilities. A detailed requirement analysis would be crucial in understanding how to build this system while catering to these specific needs.
