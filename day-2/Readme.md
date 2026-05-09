SALESFORCE : The Salesforce Platform is a cloud-based CRM (Customer Relationship Management) platform that helps businesses manage customer data, automate processes, and build applications without heavy coding.Used to store, manage, and analyze customer data. Supports low-code/no-codedevelopment. Provides tools like: Lightning App Builder Flow Builder Apex (for coding)

APP : An App in Salesforce is a collection of related components like objects, tabs, reports, and dashboards designed for a specific business function.

Object : An Object is a database table in Salesforce that stores data. Types: Standard Objects (pre-built) Account Contact Custom Objects (user-created)

TAB : A Tab is a user interface element that allows users to access objects, records, or web content. Types: Object Tab Web Tab Visualforce Tab

CONFIGURATION : Configuration means customizing Salesforce without writing code.It uses built-in tools provided by the platform. It is easy to learn and implement,Changes can be done quickly. It requires no programming knowledge. It is mainly used for simple business logic and automation

CODING : Coding means customizing Salesforce using programming languages. It uses languages like Apex, Visualforce, and Lightning Web Components (LWC). It is more complex and requires technical knowledge. Development takes more time compared to configuration. It is used for advanced and complex business requirements. It provides high flexibility and control.

Your System Design (App + Objects + User Interaction) : Example System: Student Management System App Name : Student Management App Objects: Student Object: Name Roll Number Course Course Object: Course Name Duration Fees Faculty Object: Faculty Name Subject

Relationships: Student → Course (Many-to-One) Course → Faculty (Many-to-One) Tabs: Student Tab Course Tab Faculty Tab User Interaction Flow: User logs into Salesforce Opens Student Management App Clicks on Student Tab Creates/updates student records Links student to a course Views reports and dashboards

<img width="1899" height="865" alt="Screenshot 2026-05-09 223321" src="https://github.com/user-attachments/assets/a835b49c-a1c8-480f-9332-787af8a5d107" />
