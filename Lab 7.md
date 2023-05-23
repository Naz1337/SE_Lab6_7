# Question 1

> List FOUR (4) inspection roles that you think significant to online groceries ordering system. <br> Give your reasons

Based on the given case study and class note, the following four inspection roles seem to be significant for the development of an online groceries ordering system:

1. **Author or Owner**: This role is crucial because they are the ones responsible for creating and maintaining the software. They will have the most intimate understanding of the codebase, which is essential when troubleshooting and debugging. For the given online groceries ordering system, an Author or Owner will ensure that the system's functionalities align with the client's needs, such as managing orders, registration of riders and suppliers, payment acceptance, delivery tracking, and report generation.

2. **Inspector**: The inspector is responsible for finding any errors, inconsistencies, or omissions in the software. For an online groceries ordering system, this role is extremely important to ensure that the application runs smoothly without any errors. The inspector ensures that the order processing, rider and supplier registration, payment system, and other functionalities are working as expected. Also, because the end users are computer illiterate, the software needs to be user-friendly and intuitive. The inspector plays a key role in ensuring this.

3. **Chairman or Moderator**: This role is important to manage the entire inspection process. Given that the client requires regular updates and detailed project progress reports, the Chairman or Moderator is responsible for facilitating communication between the team and the client. They will also ensure that all inspection activities are carried out according to schedule, ensuring the software is delivered within the agreed timeline of six months.

4. **Chief Moderator**: Given the technical nature of the system and the non-technical nature of the end users, continuous improvement of the system is essential. The Chief Moderator is responsible for inspection process improvements, updating checklists, and developing standards. This role ensures the software remains user-friendly, efficient, and is continuously improved upon based on feedback from users and inspection results. 

It's important to remember that these roles can overlap and one person might take on multiple roles in a smaller team. However, for a project of this scale and importance, having dedicated people in each role could ensure a smoother inspection process and a higher quality end product.

---

# Question 2

> List FOUR (4) inspection roles that you think significant to online groceries ordering system. Give your reasons

Based on the given case study and class note, the following four inspection roles seem to be significant for the development of an online groceries ordering system:

1. **Author or Owner**: This role is crucial because they are the ones responsible for creating and maintaining the software. They will have the most intimate understanding of the codebase, which is essential when troubleshooting and debugging. For the given online groceries ordering system, an Author or Owner will ensure that the system's functionalities align with the client's needs, such as managing orders, registration of riders and suppliers, payment acceptance, delivery tracking, and report generation.

2. **Inspector**: The inspector is responsible for finding any errors, inconsistencies, or omissions in the software. For an online groceries ordering system, this role is extremely important to ensure that the application runs smoothly without any errors. The inspector ensures that the order processing, rider and supplier registration, payment system, and other functionalities are working as expected. Also, because the end users are computer illiterate, the software needs to be user-friendly and intuitive. The inspector plays a key role in ensuring this.

3. **Chairman or Moderator**: This role is important to manage the entire inspection process. Given that the client requires regular updates and detailed project progress reports, the Chairman or Moderator is responsible for facilitating communication between the team and the client. They will also ensure that all inspection activities are carried out according to schedule, ensuring the software is delivered within the agreed timeline of six months.

4. **Chief Moderator**: Given the technical nature of the system and the non-technical nature of the end users, continuous improvement of the system is essential. The Chief Moderator is responsible for inspection process improvements, updating checklists, and developing standards. This role ensures the software remains user-friendly, efficient, and is continuously improved upon based on feedback from users and inspection results. 

It's important to remember that these roles can overlap and one person might take on multiple roles in a smaller team. However, for a project of this scale and importance, having dedicated people in each role could ensure a smoother inspection process and a higher quality end product.

---

# Question 3

> Compare between THREE type of software testing that will be used to test the online groceries ordering system and justify each of your answer. Put your answer in a table by highlighting the definition and example for each of the types. <br>
a. Unit testing <br>
b. System testing <br>
c. User acceptance test

Here's a comparison between unit testing, system testing, and user acceptance testing:

| Testing Type | Definition | Example |
| --- | --- | --- |
| Unit Testing | Unit testing is a level of software testing where individual components of a software are tested in isolation. The purpose is to validate that each unit of the software performs as designed. | For our online grocery ordering system, an example of unit testing might be testing the payment function to ensure it can correctly process various card types and transactions, or testing the rider and supplier registration functions to ensure they accept valid inputs and reject invalid ones. |
| System Testing | System testing is a level of software testing where a complete and integrated software is tested. The purpose of this testing is to evaluate the system’s compliance with the specified requirements. Here, the focus is on inter-component dependencies and overall behavior of the software. | In our case, system testing could involve checking the entire flow of an order, from a customer placing an order, the supplier getting notified, the rider picking up the order, to the payment being processed, to ensure all components interact correctly. |
| User Acceptance Testing (UAT) | User Acceptance Testing is a type of testing performed by the end user or the client to verify/accept the software system before moving the software application to the production environment. It is also used to replicate the environment to ensure the product meets the real-world requirements. | An example of UAT in this context would be having a select group of users (suppliers, riders, customers) from Kuantan use the system before it's officially launched. They could perform tasks such as ordering groceries, registering as a rider or supplier, making payments, etc., and provide feedback on their experiences. This would help ensure the system is ready for deployment and will meet the needs of its end-users. |

The choice of these testing types is justified by the nature of the software. 

1. Unit Testing: It is crucial because it tests individual components of the software. Given the numerous functions that this software is expected to perform (ordering, tracking, payments, registration, reporting, etc.), it is important to ensure that each of these functions works correctly on its own.

2. System Testing: As this software comprises many interacting components, system testing is necessary to ensure that these components interact correctly and the overall system functions as expected.

3. User Acceptance Testing: Given that the end-users of this system are computer illiterate and are accustomed to managing their work manually, it is vital to involve them in testing to ensure the system is user-friendly and meets their needs before it's officially launched.

---

# Question 4

> Explain how you going to implement the THREE (3) type of user testing for the online groceries ordering system.

Sure, to conduct user testing for the online groceries ordering system for LYYC, we can implement Alpha testing, Beta testing, and User Acceptance testing. Each type of testing has a different purpose and method.

**1. Alpha Testing**

Alpha Testing is usually performed in-house by internal staff. The development team and the QA team will be the primary users of the application. In our case, we can implement the following strategy:

- Our software development team and QA team will run the application to identify any potential bugs or issues that were not previously caught during unit and system testing phases.
- We will test the core functionalities like grocery ordering, rider and supplier registration, payment processing, tracking, and report generation, among others.
- Users in the Alpha testing phase will not just be testers but also developers who are familiar with the codebase. They will be able to provide insights from both a user's perspective and a developer's perspective.
- Once all the bugs and issues found during Alpha testing are fixed, the application will be ready for the next stage of testing.

**2. Beta Testing**

Beta Testing involves a limited audience outside of the software development organization. This testing phase is aimed at uncovering issues that were not discovered during Alpha testing. 

- We can identify a group of Kuantan residents, suppliers, riders, and a representation from LYYC to participate in this phase.
- Since our users are computer illiterate, we will provide a brief demonstration and guide them on how to use the system. Their feedback is crucial as it will help us understand how intuitive and user-friendly our system is for people with little to no technical knowledge.
- We will collect the feedback from the beta testers regarding the functionality, usability, reliability, and performance of the system. All bugs, errors, or other issues discovered during this stage will be addressed and resolved before moving to the final stage of testing.

**3. User Acceptance Testing (UAT)**

User Acceptance Testing is the final stage in the testing process before the system is deployed to the production environment. This stage ensures that the system meets the needs and requirements of the customer.

- A select group of end-users will use the system under realistic conditions. These end-users could include a representation from each user type: a resident (customer), a rider, a supplier, and system owner (LYYC).
- Test cases will be designed based on the requirements specified by the client (LYYC). For example, checking if a rider can register successfully, if a customer can place an order, or if a report can be generated accurately.
- The end-users will execute these test cases and if the system behaves as expected, the UAT is passed. If not, the issues will be logged, fixed, and retested until the system works as expected.
- Once UAT is successful, it means the system is ready to go live.

Each of these testing phases is critical in ensuring that the online grocery ordering system is functioning as expected, is user-friendly, and is ready to be launched. The feedback and insights from each phase will help us to refine and improve the system, ultimately ensuring its success upon deployment.

---

# Question 5

> Based on the case study, describe stages in the acceptance testing process.

Based on the case study and the class note regarding the stages in the acceptance testing process, the stages can be described as follows:

1. **Define Acceptance Criteria:** In this stage, we need to define the criteria that the software must meet to be accepted by the client. The acceptance criteria for the LYYC project could include: a web-based system for grocery ordering, a system for managing riders and supplier registrations, a system to accept payments via credit/debit cards, a delivery tracking system, and a report generation system for total income and revenue.

2. **Plan Acceptance Testing:** In this stage, we need to plan how the acceptance testing will be carried out. The testing should include all functional and non-functional requirements stated in the acceptance criteria. The plan for the LYYC project might involve several rounds of testing each component (ordering, payments, tracking, etc.), with particular attention paid to the usability of the system given the computer illiteracy of the end-users.

3. **Derive Acceptance Tests:** This stage involves creating specific tests that will verify the system meets the acceptance criteria. For the LYYC project, this might include tests for each user role (system owner, rider, supplier, customer) to confirm they can successfully perform their expected tasks. The tests should also verify that the system is able to handle the expected load and can produce accurate and useful reports.

4. **Run Acceptance tests:** In this stage, the tests are actually executed. For the LYYC project, this might involve having representatives of each user role run through the tests under the observation of the development team, possibly including simulation of peak load conditions.

5. **Negotiate Test Results:** Based on the outcomes of the tests, negotiations will take place with the client regarding any discrepancies between the acceptance criteria and the actual performance of the system. In the LYYC case, this might involve discussing how any issues might be addressed, or whether certain features might need to be modified or prioritized differently.

6. **Reject/Accept System:** This is the final stage where the client makes the decision to accept or reject the system. If the system meets all acceptance criteria, it would be accepted and delivered. If not, it would be rejected and sent back for more development or changes. For LYYC, this would be the point where they decide whether the software meets their needs and can be rolled out to their users.
