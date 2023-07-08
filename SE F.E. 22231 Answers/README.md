# Case Study

You are assigned as a member of a software development team at Advanced Software Solution Sdn Bhd. The assigned project is to develop an e-ticketing system for Kuantan Terminal Sentral (KTS), a public transport terminal. KTS is a centralized ticketing counter for all bus service providers. The KTST system (Kuantan Terminal Sentral Ticketing) is expected to replace the existing individual e-ticketing systems hosted by respective bus service providers. The KTST system will serve as a centralized e-ticketing system that can be used by customers, bus service providers, and the Kuantan Terminal Sentral management team.

Your team is required to prepare a draft of the software environment that will be used during the development until the maintenance phase. The budget allocated for this project is limited for the development stage compared to the requirement stage and design stage.

The KTST system is expected to run on the latest hardware and system architecture. It also needs to have functionalities such as (1) Passenger registration; (2) Bus service provider registration (new route or serviced offered) (3) Searching for available based on venue and travel date and time; (4) Seat availability checking; (5) Online payment and (6) Service rating.

Customers are expected to register before searching in the KTST system. Once they confirm their desired trip, they can make an online payment, and the e-ticket will be sent directly to their mobile devices. Service providers can add or remove their provided services and change the offered fees for their services. The Kuantan Terminal Sentral management team can check the overall operation of the KTST system and approve new registered bus service providers.

## Question 1

> a) Your chief developer ofKTST system development is considering an open-source tool to be used during actual system development. Discuss THREE (3) advantages and THREE (3) disadvantages of using open-source tool for KTST system.

Based on the given case study and the notes provided, we can consider the following advantages and disadvantages of using an open-source tool for the KTST system:

Advantages:

1. Cost-Effectiveness: Open-source tools are generally cheaper to acquire compared to proprietary tools, which can align with the project's limited budget for the development stage (Page 13; Chapter 6) [2].

2. Flexibility: Open-source tools tend to be more flexible and adaptable. The KTST system needs to run on the latest hardware and system architecture, and open-source tools may provide the ability to modify or tailor the tool to meet these specific needs (Page 13; Chapter 6) [2, 3].

3. Community Support: Open-source tools often have a community of users who can provide support and advice, which could be valuable given the size and complexity of the KTST system, along with its various functionalities (Page 16; Chapter 9) [3].

Disadvantages:

1. Reliability: Open-source tools may not be as reliable as proprietary ones. In terms of software reliability, the project needs to ensure high standards to fulfill the responsibilities of managing a centralized e-ticketing system (Page 13; Chapter 6) [2, 3].

2. Limited or No Dedicated Support: While there may be a community for support, open-source tools often lack a dedicated support system. In the case of complex problems or urgent issues, the team might struggle to find solutions promptly (Page 13; Chapter 6) [2].

3. Responsibility: If something goes wrong with the open-source tool, there is no one to blame but the developers themselves. This could increase the project risk, which must be carefully considered, especially given the 'what-if' scenarios presented in the project management chapter (Page 39; Chapter 5) [2, 5].

In conclusion, the decision to use open-source tools should be carefully evaluated considering the balance between cost-effectiveness, flexibility, community support, reliability, availability of dedicated support, and accountability. A thorough assessment of the tool's suitability for the project's specific requirements should be conducted to mitigate potential risks (Page 18; Chapter 9).

---

> b) Choose THREE (3) most appropriate API business model categories for KTST system. Justify your answer based on the case study.

Based on the information provided in the case study and the notes, the three most appropriate API business model categories for the KTST system would be Developer Pays, Indirect, and Developer Gets Paid.

1. Developer Pays (Page 37; Chapter 6): In this model, the developer uses the API to create something they or their organization wants. In the case of the KTST system, this model would apply as different bus service providers might pay to utilize the API for integrating their services into the centralized system. This could also cover the expenses of developing and maintaining the API as the budget is limited for the development stage (Paragraph 2).

2. Indirect (Page 37; Chapter 6): In this model, the use of the API achieves some goal that drives the core business model, provides value such as increasing awareness of specific content, or drives sales of existing products. For KTST, an indirect model might be employed where the primary goal isn't direct revenue from the API, but rather to enhance their core business—centralized e-ticketing. The API would help in expanding reach across platforms and devices, enhancing value, and extending the brand (Page 35; Chapter 6). This will foster a wider user base, providing a benefit to the bus service providers, customers, and the KTST management team (Paragraph 1 and 4).

3. Developer Gets Paid (Page 37; Chapter 6): This model involves developers receiving some sort of revenue share or direct payment as an incentive to use the API. In the case of the KTST system, this could apply if external developers or organizations are incentivized to develop additional services or applications that could enhance the KTST system. This could foster innovation and reach niche markets, providing value to the API provider (Page 35; Chapter 6). For instance, a third-party service could develop a recommendation system based on user's travel history and get paid for this.

The chosen models not only provide a possible revenue stream but also ensure that the KTST system can be dynamically extended and used by a diverse range of users (bus service providers, customers, and the management team), thus making it a more comprehensive and useful tool [3][4].

---

> c) Describe TWO (2) potential tools that might be used by developer team to develop the KTST system.

Based on the notes provided and the requirements of the KTST system outlined in the case study, two potential tools that might be used by the developer team to develop the system are an Integrated Development Environment (IDE) and Version Control System.

1. Integrated Development Environment (IDE): The IDE is an essential tool for any software development process. It provides a comprehensive set of capabilities for software development, including a source code editor, build automation tools, and a debugger, which can significantly improve productivity and code quality (Page 12; Chapter 6). As the KTST system is required to support functionalities such as passenger registration, bus service provider registration, searching for availability, seat checking, online payment, and service rating (Paragraph 3), the use of an IDE can provide the developer team with a structured environment where they can write, debug, and test their code.

2. Version Control System: A version control system is a tool that allows multiple people to work on a project at the same time without overwriting each other's changes. It can also track and provide control over changes to source code, allowing the team to revert to previous versions if necessary and track who made each change (Page 12; Chapter 6). Given the fact that the project involves a development team (Paragraph 1), the use of a version control system can help to manage the different code versions produced by different team members, providing an efficient way to handle conflicts, track changes, and maintain the integrity of the code base.

Please note that choosing the specific IDE and version control system should be based on factors like the programming language used, the team's familiarity with the tools, the complexity of the project, among others. Furthermore, the allocated budget for the development stage must also be considered (Paragraph 2), which might limit the selection to free or low-cost options available. 

In the broader software development process, additional tools for testing, profiling, debugging, code coverage, and others would be beneficial to ensure the reliability and quality of the final software product (Page 12; Chapter 6). Moreover, software project management techniques and risk management (Page 45; Chapter 5), as well as software verification and validation strategies (Page 37; Chapter 7), should also be applied to ensure the project's success.

## Question 2

> a) Distinguish the differences between these two activities: software inspections and software testing? Justify TWO (2) reasons why both of these activities are important to the verification process in the KTST system development life cycle.

Software inspections and software testing are two essential activities within the software development life cycle that serve different but complementary purposes.

Software inspections involve a thorough examination of the static system representation with the aim of discovering anomalies and defects (Page 16; Chapter 7). During inspections, people examine the source code to find issues, and these inspections do not require the execution of the system, meaning they can be used before implementation (Page 16; Chapter 7). They may be applied to any representation of the system, including requirements, design, configuration data, test data, and others (Page 16; Chapter 7).

On the other hand, software testing is concerned with exercising and observing product behavior, or dynamic verification (Page 8; Chapter 7). The system is executed with test data and its operational behavior is observed (Page 8; Chapter 7). Testing is designed to discover system defects (defect testing) and show that the software meets its requirements (validation testing) (Page 11; Chapter 7).

In the context of the KTST system development, both of these activities hold paramount importance for a few reasons.

First, considering the limited budget allocated for the development stage compared to the requirement stage and design stage (Paragraph 2), it is crucial to discover and rectify any anomalies and defects at the earliest possible stages of the software development. Software inspections would allow the team to uncover issues before the implementation stage, saving costs associated with late-stage alterations (Page 16; Chapter 7). 

Second, given the complexity of the KTST system, which includes a variety of functionalities such as passenger registration, service provider registration, search functionality, seat availability checking, online payment, and service rating (Paragraph 3), comprehensive software testing is needed to ensure that each function meets its requirements (Page 11; Chapter 7). The software must be thoroughly tested to ensure it behaves as expected under a variety of scenarios, maintaining the trust of its users, including the customers, bus service providers, and the Kuantan Terminal Sentral management team (Paragraphs 3 and 4).

Overall, both software inspections and software testing are fundamental in the software verification process, each offering a unique approach to ensuring the quality and reliability of the final product. By employing both methods, the team can effectively verify conformance with specifications (software inspections) and validate that the developed system meets the end-users' needs (software testing) (Page 4; Chapter 7).

---

> b) Describe TWO (2) roles that are responsible during the inspection activities of KTST system

In the context of the KTST system and based on the information provided in the notes, two roles that are crucial during the inspection activities are the "Inspector" and the "Chairman or Moderator".

The Inspector is the programmer or designer who is responsible for producing the program or document and fixing the defects discovered during the inspection process. In the context of the KTST system, this individual would need to scrutinize the system for any potential errors, omissions, or inconsistencies that could affect the functionality of the system such as Passenger registration, Bus service provider registration, Searching for available based on venue and travel date and time, Seat availability checking, Online payment, and Service rating (Paragraph 3; Case Study). As part of their role, the Inspector may also need to identify broader issues that are outside the scope of the inspection team, which could include potential scalability or integration issues for the system (Page 23; Chapter 7).

The Chairman or Moderator manages the inspection process and facilitates the inspection meetings. They are also responsible for reporting the process results to the Chief Moderator. For the KTST system, the Chairman or Moderator would need to ensure that all aspects of the system are thoroughly inspected, including how it will be used by different stakeholders such as the customers, bus service providers, and Kuantan Terminal Sentral management teams (Paragraphs 1, 4; Case Study). They would also have to ensure that any modifications needed to repair discovered errors are addressed and, if necessary, that a re-inspection is conducted (Page 22; Chapter 7).

Both of these roles play a significant part in ensuring the reliability and effectiveness of the KTST system, and that it can efficiently serve the various needs of its stakeholders.

---

> c) To ensure KTSK system will perform well and meet the users requirement, describe THREE (3) types of software testing that will be used to test the KTST system. Provide ONE (1) justification for each type, explaining why those types of software testing are important to the KTST system development.

Based on the requirements of the Kuantan Terminal Sentral Ticketing (KTST) system from the case study and the concepts of software testing from the given notes, three types of software testing can be employed. 

1. **Development Testing** 

   This kind of testing is done during the system development to find bugs and defects (Page 37; Chapter 7). It includes Unit Testing, Component Testing, and System Testing (Page 39; Chapter 7). Given the complex functionalities of KTST, like passenger registration, service provider registration, and online payment, it is necessary to ensure that each functionality (unit) and their interactions (components) work as expected. Development testing can help identify issues at the early stage, thus reducing the overall cost of development [3].

2. **User Acceptance Testing (UAT)** 

   This type of user testing determines whether the system is ready to be accepted and deployed in the user environment (Page 45; Chapter 7). This is particularly relevant for KTST system as it is a system intended to be used by different user types: customers, bus service providers, and Kuantan Terminal Sentral management teams. Each user group will have different requirements and expectations, and UAT ensures that the system meets these diverse needs [4]. 

3. **System Testing**

   It focuses on testing the interactions between components (Page 50; Chapter 7). For the KTST system, this is crucial as it is designed to run on the latest hardware and system architecture, with several functionalities interacting with one another. For example, a customer's online payment should trigger the sending of e-tickets, and the management team should be able to check the overall operations of the KTST system [3]. The interaction between these components needs to be verified to ensure smooth system operations.

It is important to note that software reliability can be used to evaluate the progress of system testing (Page 19; Chapter 9). By monitoring the failure intensity of KTST during testing, one can understand the reliability of the system and measure how close the system is to its goal [3].

## Question 3

> a) Since Kuantan Terminal Sentral management team spend huge investments for KTST systems development, they treat it as their future critical business assets. To maintain the value of KTST which become the asset to the business, it must be evolved. Discuss THREE (3) types of system maintenance strategy to ensure KTST system able to operate in a longer period.

To ensure the Kuantan Terminal Sentral Ticketing (KTST) system can operate over a longer period, it's critical to apply appropriate system maintenance strategies. Based on the provided case study and the notes, I recommend the following strategies:

1. **Maintenance to repair software faults**. This type of maintenance involves correcting any deficiencies in the system's performance to ensure that it meets its intended requirements (Page 23; Chapter 8). Given the various functionalities that the KTST system is expected to have, such as passenger registration, seat availability checking, and online payment, it is highly likely that software faults may occur. Therefore, it's essential to regularly monitor the system and promptly address any issues to keep the system operating smoothly.

2. **Maintenance to adapt software to a different operating environment**. The KTST system needs to adapt to potential changes in its operating environment, such as new hardware or system architectures (Page 23; Chapter 8). Given that the system is expected to run on the latest hardware and system architecture (Paragraph 3), it's likely that these components may change over time. It will be necessary to regularly review and adapt the system to these changes to ensure its compatibility and optimal performance.

3. **Maintenance to add or modify the system’s functionality**. The system's functionalities may need to be updated to satisfy new requirements (Page 23; Chapter 8). Considering that the KTST system is designed to serve customers, bus service providers, and the Kuantan Terminal Sentral management team, the needs of these user groups may evolve over time. For example, new features may be required, or existing features may need to be updated to better serve these users (Paragraph 4). Therefore, the system needs to be regularly evaluated and updated to align with changing needs.

When implementing these strategies, it's important to keep in mind factors that can impact the cost of maintenance. These include the stability of the team maintaining the system, the contractual responsibility of the developers, the skills of the maintenance staff, and the age and structure of the program (Page 27; Chapter 8). 

Finally, it's crucial to periodically assess the system quality and business value (Page 44, 49, 47; Chapter 8) and use complexity metrics to predict system maintainability (Page 31; Chapter 8). This will help in making informed decisions about when to maintain, replace, or re-engineer the system, ensuring that it continues to be a valuable asset to the business.

---

> b) In the case study, the existing individual e-tiketing systems hosting by respective buses service providers are categorised as legacy system. Kuantan Terminal Sentral mangement team considered this system has low quality and low business value to them because they are operated separately and lead to inefficient operation to them as well as to the customer. What is the best legacy system management strategy in dealing with those system? Give your justification for your answer.

Based on the provided notes and the case study, the best legacy system management strategy for Kuantan Terminal Sentral (KTS) in dealing with the existing e-ticketing systems would be to "replace the system with a new system" (Page 44; Chapter 8). 

This strategy is suggested due to several reasons:

1. Low Quality and Low Business Value: The existing e-ticketing systems are categorised as low quality and low business value (Page 46; Chapter 8). This is due to their operation in silos, causing inefficiencies for KTS and its customers. A centralized e-ticketing system would eliminate these inefficiencies, thus increasing the business value of the system.

2. New Functionalities: The new KTST system is expected to run on the latest hardware and system architecture, and it needs to support various functionalities such as passenger registration, service provider registration, service availability checking, online payment, and service rating [Paragraph 3]. These functionalities are not supported by the existing systems, thus necessitating the replacement with a new system.

3. Efficiency and Convenience: The replacement strategy aligns with KTS's goal of centralizing its ticketing operations. The new system would offer an improved experience to customers by enabling online ticket purchases and providing e-tickets directly to their mobile devices [Paragraph 4]. It would also enable service providers to modify their offered services conveniently, and allow KTS management to oversee the operations effectively.

4. Cost Considerations: From the perspective of cost, the budget for the project is limited for the development stage [Paragraph 2]. Therefore, maintaining or re-engineering the existing low-quality systems may end up being costlier in the long run, considering factors such as team stability, staff skills, and system age and structure (Page 27; Chapter 8). 

Therefore, replacing the legacy systems with a new, centralized e-ticketing system would provide the most efficient and cost-effective solution for Kuantan Terminal Sentral, enhancing both the customer experience and the operational efficiency.

---

> c) Discuss TWO (2) possible situations that lead to urgent changes need to be implemented for KTST system during system evolution stage.

Given the case study of the KTST system, there are several possible situations that could lead to the need for urgent changes during the system's evolution stage.

1. **System Compatibility with Hardware and System Architecture**
   
    One urgent change that may arise is related to the system's compatibility with the latest hardware and system architectures. Since the KTST system is expected to run on the latest hardware and system architecture (Paragraph 3), changes in these technologies could have unexpected effects that require immediate attention to ensure the system remains operational. For instance, an operating system (OS) upgrade could unexpectedly affect the functioning of the KTST system, requiring an urgent software modification to rectify any issues and restore normal operation. This aligns with the point on urgent changes that may have to be implemented without going through all stages of the software engineering process, especially when changes to the system's environment have unexpected effects (Page 13; Chapter 8).

2. **Changes in Business Environment**
   
    Another situation could arise from changes in the business environment. For example, a new policy or regulation might require the KTST system to incorporate additional features or modify existing ones urgently, such as enhanced security protocols or modifications to the online payment process. Similarly, the release of a competing product with advanced features may require the KTST system to rapidly innovate and introduce new or improved functionalities to maintain competitive advantage. Both of these examples involve urgent changes that demand a quick response to maintain normal operation and meet business requirements (Page 13; Chapter 8).

It's crucial to understand that software evolution is an inevitable part of a software system's lifecycle due to changing system requirements, evolving business environments, and enhancements in technologies (Page 4; Chapter 8). Implementing these urgent changes often requires an iteration of the development process where the revisions to the system are designed, implemented, and tested (Page 12; Chapter 8). However, during this process, it is important to consider the impact of these changes on the entire system, taking into account the software's structure, functionality, and how the proposed change might affect it (Page 12; Chapter 8).

---

> d) Discuss THREE (3) maintenance cost factors that should be considered by Kuantan Terminal Sentral Management team that may increase the maintenance cost of the KTST system.

The maintenance cost of the Kuantan Terminal Sentral Ticketing (KTST) system is influenced by several factors as outlined in the notes from Chapter 8: Software Evolution. Here are three key factors that the Kuantan Terminal Sentral Management team should consider:

1. **Team Stability** (Page 27; Chapter 8): The maintenance cost can rise if there is frequent turnover within the staff responsible for maintaining the system. Ensuring that the same team is involved with maintenance over an extended period of time can help reduce costs, as they will develop familiarity and expertise with the system. In the context of the KTST system, keeping the same team responsible for its maintenance could streamline problem-solving and decrease the time it takes to resolve issues, thereby reducing overall costs.

2. **Staff Skills** (Page 27; Chapter 8): The skill level of the maintenance team can greatly influence maintenance costs. If the maintenance staff are inexperienced or have limited domain knowledge, they may take longer to solve problems or might implement solutions that are not optimal, thus escalating costs. Therefore, the management team should ensure that their maintenance staff is well-trained and knowledgeable about the system. This becomes even more relevant in the case of KTST system as it is expected to run on the latest hardware and system architecture (Paragraph 3), which requires up-to-date knowledge and skills to maintain.

3. **Program Age and Structure** (Page 27; Chapter 8): As software programs age, their structure tends to degrade, making them harder to understand and change. This increased complexity and degradation can lead to higher maintenance costs. Since the KTST system will replace the existing individual e-ticketing systems and is expected to serve as a centralized e-ticketing system (Paragraph 1), it will likely evolve over time with added functionalities and features, which could result in increased complexity. Hence, it's essential to plan for this potential increase in maintenance costs as the system ages.

Also, it's important to bear in mind that the KTST system will likely require maintenance beyond simple fault repairs. For example, changes might be required to adapt to a different operating environment or to satisfy new requirements (Page 23; Chapter 8), which could potentially increase maintenance costs.

References: Chapter 8: Software Evolution (Pages 23, 27) [1, 4].

## Question 4

> a) Differentiate between FAILURE and FAUL, by providing appropriate example from the case study.

In software reliability, "failure" and "fault" are two fundamental concepts. Failure is said to occur when the observable outcome of a program execution is different from the expected outcome. For instance, if the newly developed KTST system is expected to send e-tickets to the customers' mobile devices after an online payment (Paragraph 4), but instead, the system fails to send the e-tickets, this would be considered a failure. It's a deviation from the expected outcome of the software's execution.

On the other hand, the adjudged cause of such failure is called a fault (Page 7; Chapter 9). This could be due to various reasons, such as a block of code not working as expected, or incorrect software logic. If we take the above example of the KTST system failing to send e-tickets, the fault could be a defective code block that handles the sending of e-tickets after payment. This block of code, which is the fault, causes the failure that the users experience.

Therefore, failure and fault, while related, have distinct differences. Failure refers to the observed incorrect behavior of a software system, whereas a fault refers to the underlying cause of that failure.

---

> b) The following are reliability requirement statements of a software system:

> "The client of the KTST system has stated that the reliability requirement is that no more than two (2) faults may occur during every eight (8) hours of continuous operation. Testing begins when the software reaches the beta phase. Four (4) employees perform continuous testing during business hours."

> Based on the reliability requirement statements above, please provide the formulas used for each calculation: <br>
i. Calculate the failure rate goal based on per-hour operation.<br>
ii. Determine the cumulative software testing time performed by the employees within a day.<br>
iii. Compute the daily failure intensity goal performed by the employees.

Sure, I'll walk through each calculation in the order they are presented.

**i. Calculate the failure rate goal based on per hour operation.**

From the reliability requirement, we have no more than 2 faults may occur every 8 hours of continuous operation. 

The failure rate is calculated by taking the total number of failures and dividing by the total time of operation. In this case, it is given as 2 failures per 8 hours.

So, the failure rate goal can be calculated as follows:

Failure rate goal = Number of failures / Hours of operation
                          = 2 failures / 8 hours
                          = 0.25 failures/hour (Page 11; Chapter 9)

**ii. Determine the cumulative software testing time performed by the employee within a day.**

In the given scenario, it is stated that there are four employees performing continuous testing during business hours. Assuming standard business hours to be 8 hours per day, the cumulative software testing time can be calculated by multiplying the number of testers by the number of hours of testing performed.

So, the cumulative software testing time is:

Cumulative software testing time = Number of testers * Number of hours
                                                   = 4 testers * 8 hours
                                                   = 32 tester-hours (Page 11; Chapter 9)

**iii. Compute a day failure intensity goal performed by the employees.**

The failure intensity goal is computed by multiplying the failure rate goal by the cumulative software testing time. From our previous calculations, we have a failure rate goal of 0.25 failures/hour and cumulative software testing time of 32 tester-hours.

So, the daily failure intensity goal can be calculated as follows:

Failure intensity goal = Failure rate goal * Cumulative software testing time
                                 = 0.25 failures/hour * 32 tester-hours
                                 = 8 failures/day (Page 11; Chapter 9)

Regarding the case study, the reliability requirement is essentially about ensuring that the software developed for the Kuantan Terminal Sentral Ticketing (KTST) system is able to function with a maximum of 2 faults occurring every 8 hours of operation, throughout the testing phase. This is indicative of the level of quality and reliability the client expects from the software system, which also underlines the need for adequate and rigorous software testing, especially given the operational profile of the KTST system, which serves various stakeholders (Paragraph 1; Paragraph 3).

In addition, considering the limited budget for the development stage in comparison to the requirement and design stages (Paragraph 2), it's critical to maintain the prescribed reliability requirements to avoid costly fixes or system overhauls later. Maintaining reliability is also crucial to the overall success of the project in order to satisfy the various needs of customers, service providers, and management teams (Paragraph 4).

---

> c) Explain THREE (3) advantages of reliability specification in the context of KTST system.

Reliability specification plays a crucial role in developing the KTST system, providing several key benefits.

1. **Improved User Experience:** A reliable system assures that users can trust the system to function as expected. It's essential that users can register, search for available buses, check seat availability, make online payments, and rate services without system failures (Paragraph 3). A reliable system, thus, enhances user satisfaction and promotes system usage. Any system failure can lead to frustration, negatively impacting the user's perception of reliability (Page 15; Chapter 9).

2. **Efficient Resource Utilization:** As the budget for the development phase is constrained compared to the requirement and design stages (Paragraph 2), it's crucial to optimize resource usage. Implementing a reliable system from the start reduces the need for later rectifications due to system failures, leading to better resource allocation and cost-effectiveness. A reliability specification ensures that the system is designed and developed to minimize failures (Page 24; Chapter 9).

3. **Facilitated System Management:** A reliable system benefits not just the end users, but also the service providers and the Kuantan Terminal Sentral management team (Paragraph 1). The management team can better oversee the system's operations, and service providers can conveniently update their services, assured that system errors won't hinder their activities. This contributes to the smooth running of the terminal operations. The more reliable the system, the less downtime and the fewer resources are needed for troubleshooting and repairs, therefore, maintaining productivity and efficiency (Page 6; Chapter 9).

In summary, a reliability specification is not just a technical requirement but a user-centric approach that greatly benefits the overall system operations and user experience while optimizing resource allocation in the KTST system development. [3]

---

> d) Software failures can cause inconvenience to the users of the software. In your opinion, is it ethical or not for companies to release software that they know including faults that could lead to software failures?<br>
Explain FOUR (4) consequences resulted if KTST has faults but been released to the
customer.


### Answer 1

Releasing software that knowingly includes faults that could lead to failures is generally considered to be unethical. Although there may be business reasons for doing so, such as getting the product to market quickly, the risks and potential harm to the users and stakeholders often outweigh the benefits. The principle of 'do no harm' is a cornerstone of many professional ethics codes and applies in the context of software development as well (Page 7; Chapter 7).

The ethical implications are particularly apparent in the context of the KTST system development. Should it be released with known faults, there would be several consequences.

1. **Inconvenience to Users**: Known faults in the system could lead to software failures that disrupt the user's ability to use the system as expected. This could result in an inability to register, check seat availability, make payments, or use other system features. These disruptions could cause significant inconvenience and frustration for the users (Paragraph 3).

2. **Negative Impact on Bus Service Providers**: Faults in the system could also negatively affect bus service providers. If they are unable to effectively manage their services, such as adding new routes or changing fees, it could impact their business operations and revenue. Providers might also face customer complaints and negative reviews due to problems caused by the system (Paragraph 4).

3. **Operational Issues for Kuantan Terminal Sentral Management**: Management teams rely on the KTST system to monitor and manage operations. Faults in the system could hamper their ability to do so effectively. This could lead to inefficiencies and operational issues, and potentially larger organizational issues if they are unable to approve new bus service providers in a timely manner (Paragraph 4).

4. **Risk and Cost Increases**: Releasing a faulty system could also lead to increased risks and costs in the long term. The company would likely have to spend more time and resources on fixing the faults after the release, possibly diverting them from other important tasks. Additionally, the system's reputation may be damaged, resulting in lost customers and revenue. It could also lead to further costs if the company faces legal action or has to compensate users for issues caused by the system faults (Page 39; Chapter 5).

In conclusion, while software failures can and do happen even with the best efforts to avoid them, knowingly releasing faulty software is unethical and can have far-reaching negative consequences. Companies should strive to uphold high ethical standards and prioritize software reliability to avoid such issues (Page 27; Chapter 9).

### Answer 2

Releasing software known to include faults that could lead to failures can indeed raise ethical concerns. If a company is aware of such faults, it has the responsibility to address them before deploying the software to ensure the best user experience and maintain trust with its customers. 

This ethical responsibility can be seen even more clearly in the context of the Kuantan Terminal Sentral Ticketing (KTST) system case. Given that the KTST is expected to be a centralized system serving a wide range of stakeholders - customers, bus service providers, and Kuantan Terminal Sentral management team, it is critical that the system performs as expected to avoid potential negative consequences.

1. **Customer Inconvenience**: If the KTST system has faults, customers may face difficulties while registering, searching for available buses, checking seat availability, making online payments, or receiving their e-tickets. This could result in inconvenience, frustration, or even financial losses, and customers may lose trust in the system or the service it provides (Page 15; Chapter 9)[3,4].

2. **Operational Issues for Bus Service Providers**: Service providers rely on the KTST system for registration, service updates, and managing service fees. Faults in the system could cause inaccurate data entry or retrieval, affecting their ability to provide effective services and potentially leading to financial losses or damaged reputations (Page 15; Chapter 9)[3].

3. **Management Challenges**: For the Kuantan Terminal Sentral management team, a faulty KTST system could impede their ability to oversee operations effectively. They might face issues while approving new bus service providers or checking the overall system's operation. This could lead to operational inefficiencies and increased costs (Page 15; Chapter 9)[4].

4. **Damage to the Software Developer's Reputation**: Advance Software Solution Sdn Bhd, as the developer of the system, risks damaging their reputation by releasing a faulty software. Such a situation can lead to loss of trust among current and potential clients, impacting future business prospects (Page 15; Chapter 9)[3].

The developers can improve the system's reliability by implementing various approaches such as fault avoidance, fault detection and removal, and fault tolerance (Page 24; Chapter 9). Also, considering the users' operational profile and taking into account the system's complexity, development process, personnel quality, and operational environment can help ensure the system is reliable (Page 27; Chapter 9)[3,4].

Thus, it is not only ethically vital but also operationally sound to ensure that the software released is as fault-free as possible to avoid causing inconvenience and potential harm to the system's various users[1,2,3,4].















