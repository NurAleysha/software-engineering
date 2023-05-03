#  Proposal 

## UTM ONLINE GRADING SYSTEM


### Prepared by: 
  1. VINESH A/L VIJAYAKUMAR A22EC0290
  2. NAVACHANDER NAVASANTAR A22EC0226
  3. NAVASARATHY A/L S.GANESWARAN A22EC0091
  4. MUHAMMAD NUR AZHAR BIN MOHD YAZID A22EC0220

### Table of Contents
- [Executive Summary](#1-executive-summary)
- [Background](#2-background)
- [Objectives](#3-objectives)
- [Scope](#4-scope)
- [Sofware Process Model](#5-software-process-model)
- [Budget](#6-budget)
- [System Architecture](#7-system-architecture)
- [Risk Assessment](#8-risks-assessment)
- [Resources](#9-resources)
- [Technical Specification](#10-technical-specifications)
- [Timeline and Deliverables](#11-timeline-and-deliverables)
- [Conclusion](#12-conclusion)
  
### 1. Executive Summary
- The UTM online grading system is a project that seeks to enhance the grading process for students and faculty members at the University of Technology, Malaysia. The project's goal is to develop a digital platform that will enable real-time grading, monitoring of student progress, and generation of reports. The system will also provide students with access to their grades, schedules, and academic progress reports. By improving accuracy and fairness in grading, reducing administrative overheads, and enhancing the student experience, the project aims to increase academic performance, engagement, and satisfaction while improving overall institutional efficiency. Ultimately, the UTM online grading system will support the university's mission of delivering a high-quality education that prepares students for success in a rapidly evolving global economy.

### 2. Background:
- The UTM online grading system is a software project aimed at improving the grading process for students and faculty members at the University of Technology, Malaysia. The proposal seeks to address the challenges posed by the traditional paper-based grading system, such as delays and inaccuracies in grading, and difficulties in tracking student progress. 
- The project aims to develop a digital platform that will streamline the grading process and provide benefits such as faster grading, greater transparency and accountability, and improved communication. By adopting a digital platform for grading and record-keeping, the university will become more efficient and better equipped to provide a high-quality education to its students in a rapidly evolving global economy.

### 3. Objectives:
- To develop a digital platform for real-time grading that improves accuracy, transparency, and accountability, reducing errors and delays associated with traditional paper-based grading systems.
- To provide a centralized system for recording and tracking student progress, enabling faculty members to monitor academic performance and provide timely feedback to students.
- To enable students to access their grades, schedules, and academic progress reports in real-time, improving their understanding of their progress and enhancing their learning experience.
- To reduce administrative overheads associated with grading and record-keeping, allowing faculty members to focus on teaching and research activities, improving institutional efficiency and productivity.
- To enhance the overall student experience by providing a modern, user-friendly interface for grading and record-keeping, improving engagement and satisfaction with the university's academic processes.

### 4. Scope: 
<img src="https://user-images.githubusercontent.com/128279581/235497036-561d13d0-1bf0-4de7-b042-b2b3a10bdd1e.png" alt="Scope"></img>


- User Authentication: The system should allow instructors and students to authenticate themselves using their UTM credentials.
- Grading Management: The system should allow instructors to create and manage grading components, such as assignments, quizzes, and exams, and assign grades to       
  students for each component.
- Grade Calculation: The system should automatically calculate and display final grades based on the grading components and their weightage, as well as handle any special grading policies, such as dropping the lowest grade.
- Grade Submission: The system should allow instructors to submit grades to the university's official grading system.
- Grade Viewing: The system should allow students to view their grades for each component, as well as their overall course grade.
- Feedback and Communication: The system should allow instructors to provide feedback to students on their performance and communicate with them through the system.
- Course Management: The system should allow instructors to manage their course details, such as course description, schedule, and syllabus.
- Accessibility: The system should be accessible to users with disabilities, and support assistive technologies such as screen readers.
- Security: The system should be designed with appropriate security measures to ensure the privacy and confidentiality of student information and grading data.

### 5. Software Process Model:
This section describe the ideal software process model for this system development. The write-up must consist of:
- The goal of the software process model is to provide a systematic and structured approach to software development that maximizes efficiency, reduces risk, and improves the overall quality of the UTM online grading system.
- For the UTM online grading system, the ideal software process model would be the iterative and incremental model. The iterative and incremental model is a flexible and adaptable approach that involves a series of iterations, each consisting of planning, designing, developing, testing, and delivering phases. This model is ideal for projects where requirements are likely to change or evolve, as it allows for flexibility and adaptability.
<br></br>
**Here's an illustration of the Incremental Model for the development of UTM Grading System:**

1.Planning: In this phase, the project team meets with stakeholders to define the project scope, requirements, and timelines. The deliverables in this phase can include a project plan, requirements specification document, and project schedule.

2.Requirements: In this phase, the project team identifies and documents the functional and non-functional requirements of the grading system. The deliverables in this phase can include a requirements document, use cases, and user stories.

3.Design: In this phase, the project team creates a detailed design for the grading system. This includes designing the user interface, database schema, and system architecture. The deliverables in this phase can include wireframes, system architecture documents, and database schema documents.

4.Implementation: In this phase, the project team develops and implements the grading system. The development is done in small increments or modules, with each module developed and tested separately. The deliverables in this phase can include source code, unit test cases, and user documentation.

5.Integration: In this phase, the developed modules are integrated and tested to ensure that they work together as expected. The deliverables in this phase can include integration test cases and test reports.

6.Deployment: In this phase, the grading system is deployed to the production environment. The deliverables in this phase can include deployment plans, user manuals, and training materials.

7.Maintenance: In this phase, the grading system is maintained to ensure that it continues to function as expected. The deliverables in this phase can include maintenance plans, bug reports, and system documentation.

For testing methodologies, unit testing can be used to test each module of the grading system individually to ensure that it is working as expected. Integration testing can then be used to test the integration of the modules to ensure that they are working together correctly. System testing can be used to test the system as a whole to ensure that it meets the specified requirements, and acceptance testing can be used to verify that the grading system meets the user's needs.

For project management practices, Agile or Scrum can be used to help manage the project. These methodologies involve breaking down the development process into smaller sprints or iterations, which helps to improve collaboration between team members and allows for more flexibility in adapting to changing requirements. Project management tools such as Jira, Trello, or Asana can be used to track progress and assign tasks.

In terms of quality assurance processes, code reviews and software inspections can be used to ensure the quality of the code. This involves reviewing the code for errors or defects, ensuring that it adheres to coding standards, and making any necessary improvements. Automated testing tools such as Selenium or JUnit can also be used to automate testing and reduce the risk of human error.

A Gantt chart or any suitable project management tool can be used to help plan and track progress throughout the development process. This will help to ensure that the project stays on schedule and that all tasks are completed as planned.
```sql

example of grantt chart based on our project:
-----------------------------------------------------------------------------------------------------------------------
| Phase         | Task                                                            | Start Date | End Date  | Duration |
| ------------- | ----------------------------------------------------------------| ---------- | ----------| -------- |
| Planning      | Meet with stakeholders                                          | 2023-05-10 | 2023-05-17| 1 week   |
| Planning      | Define project scope, requirements, and timelines               | 2023-05-18 | 2023-05-24| 1 week   |
| Planning      | Create project plan, requirements spec, and schedule            | 2023-05-25 | 2023-06-07| 2 weeks  |
-----------------------------------------------------------------------------------------------------------------------
| Requirements  | Identify and document functional and non-functional req.        | 2023-06-08 | 2023-06-21| 2 weeks  |
| Requirements  | Create requirements document, use cases, and user stories       |2023-06-22  |2023-07-05 |2 weeks   |
-----------------------------------------------------------------------------------------------------------------------
| Design        | Design user interface, database schema, and system arch.        | 2023-07-06 | 2023-07-26| 3 weeks  |
| Design        | Create wireframes, system architecture docs, and DB schema docs | 2023-07-27 | 2023-08-09| 2 weeks  |
-----------------------------------------------------------------------------------------------------------------------
| Implementation| Develop and implement grading system modules                    | 2023-08-10 | 2023-10-04| 8 weeks  |
| Implementation| Develop and test modules separately                             | 2023-08-10 | 2023-10-04| 8 weeks  |
| Implementation| Create source code, unit test cases, and user doc.              | 2023-10-05 | 2023-10-18| 2 weeks  |
-----------------------------------------------------------------------------------------------------------------------
| Integration   | Integrate and test developed modules                            | 2023-10-19 | 2023-11-01| 2 weeks  |
| Integration   | Ensure modules work together as expected                        | 2023-10-19 | 2023-11-01| 2 weeks  |
-----------------------------------------------------------------------------------------------------------------------
| Deployment    | Deploy grading system to production environment                 | 2023-11-02 | 2023-11-15| 2 weeks  |
| Deployment    | Create deployment plans, user manuals, and training mat.        | 2023-11-02 | 2023-11-15| 2 weeks  |
-----------------------------------------------------------------------------------------------------------------------
| Maintenance   | Maintain grading system to ensure it functions as expected      | 2023-11-16| 2024-05-31| 26 weeks  |
| Maintenance   | Create maintenance plans, bug reports, and system docs.         | 2023-11-16| 2024-05-31| 26 weeks  |
-----------------------------------------------------------------------------------------------------------------------
```


### 6. Budget:
The development of the academic course registration system for 30,000 users within a year will involve various costs, including hardware, software, contigency, and testing. The budget for this project is estimated at **RM 315,000**, as outlined below:

- **Hardware Costs: RM 100,000** <br>
Server Hardware: RM50,000.Total Hardware Costs = RM50,000
- **Software Costs: RM 75,000** <br>
Development Software: RM5,000.
Database Management System: RM10,000.
Web Hosting Service: RM5,000 per month x 8 months = RM40,000.
- **Personnel Costs: RM 80,000** <br>
Developer Salary: RM3000 per month per developer x 3 developers x 8 months = RM24,000.Project Manager Salary: **RM7,000** per month x 8 months = RM56,000.

- **Testing Costs: RM 140,000** <br>
Personnel: 2 testers for 3 months.
Tester Salary: RM20,000 per month per tester x 2 testers x 3 months = RM120,000.
Software Testing Tools: RM20,000.
Contingency: 10% of Total Costs.
Contingency Costs = RM14,000

- **Other Expenses: RM 100,500** <br>
This includes the cost of rent for office space, utilities, marketing and advertising, and testing.

In conclusion, the estimated budget for the development of the UTM Event Management System is RM 315,000. The budget will cover the costs associated with hardware, software, personnel, testing, and contingency. Any changes in the budget will be communicated to stakeholders and project sponsors.

### 7. System Architecture:
- Overview:
The UTM Grading System will be a web-based application that allows lecturers to input, manage, and analyze grades for their courses. The system will be designed to be scalable and flexible, allowing for future updates and enhancements. The system will be built using modern web technologies and frameworks to ensure compatibility, security, and ease of maintenance.
- Data Storage and Management:
The UTM Grading System will utilize a Relational Database Management System (RDBMS) to store and manage data. The database will be hosted on a dedicated database server that will be accessed by the web server hosting the application. The database schema will be designed to optimize data retrieval and ensure data integrity. Data backups will be regularly performed to ensure data security.
- The proposed system architecture for the event management system will be a web-based system built using modern technologies and frameworks. The system will use the following tools and technologies:

- Programming languages: HTML, CSS, JavaScript, PHP
- Frameworks: Laravel, Bootstrap
- Database: MySQL
- Server: Apache
- Data Visualization: Chart.js
The system will have a multi-tier architecture consisting of a presentation layer, application layer, and data layer. The presentation layer will be responsible for displaying the user interface and handling user interactions. The application layer will be responsible for implementing the business logic of the system and handling user requests. The data layer will be responsible for storing and managing data.
- Provide a flowchart or block diagram of the system architecture.

- Flowchart:
 
```sql
    
+---------------------+       +------------------------+       +-----------------------+
|                     |       |                        |       |                       |
| Presentation Layer  +------->     Application Layer   +------->      Data Layer      |
|                     |       |    (Laravel Framework)  |       |    (MySQL, RDBMS)    |
+---------------------+       +------------------------+       +-----------------------+
```


- Block Diagram: 
          
```sql
               +------------------+
               |     Web Server   |
               |   (Apache, PHP)  |
               +------------------+
                        |
                        |
               +------------------+
               |   Application    |
               |   (Laravel)      |
               +------------------+
                        |
                        |
               +------------------+
               |  Database Server |
               |  (MySQL, RDBMS)  |
               +------------------+
                        |
                        |
               +------------------+
               |     Database     |
               +------------------+

```
### 8. Risks Assessment:
Risk assessment is an essential part of any software development project, and the UTM Grading System project is no exception. The following is a risk assessment and management plan for the project.
#### 1. Technical Challenges: 
The development team will conduct a thorough analysis of the technical requirements of the system and assess the feasibility of the proposed solution. The team will also conduct regular code reviews and testing to identify and address any technical challenges promptly.

#### 2. Resource constraints: 
The project manager will monitor the project budget and schedule regularly to ensure that resources are allocated effectively. The project manager will also identify any personnel shortages or hardware/software limitations and take appropriate action.

#### 3. Changes in project requirements: 
The development team will conduct regular stakeholder meetings to review project requirements and identify any changes. The team will also document all changes and assess their impact on the project timeline and budget.

#### 4. Security breaches: 
The development team will follow industry best practices for data security, including encryption of sensitive data, regular security audits, and penetration testing. The team will also implement security protocols and procedures to prevent unauthorized access to the system.
#### 5. Server Downtime: 
The development team will implement a backup and recovery plan to minimize the impact of server downtime. The team will also work with the hosting provider to ensure that the server is maintained and updated regularly to minimize the risk of downtime.

### 9. Resources
#### Staff
- Project Manager: responsible for overseeing the project, managing resources, and ensuring the project is delivered on time and within budget.
- Business Analyst: responsible for gathering and analyzing requirements, creating functional specifications, and identifying system requirements.
- Developers: responsible for building and implementing the system.
- Quality Assurance (QA) Analysts: responsible for testing the system and ensuring that it meets requirements and is bug-free.
- Technical Writers: responsible for creating user manuals and system documentation.
- User Experience (UX) Designers: responsible for creating an intuitive and user-friendly interface.

#### Equipment
- Server infrastructure: a robust server infrastructure is required to host the grading system and ensure it can handle large volumes of traffic.
- Network infrastructure: high-speed internet connectivity and network equipment to connect the system to the internet and the university network.
- Workstations: computers for the development and QA teams.

#### Software
- Programming languages: the system can be built using different programming languages and frameworks, depending on the preferences and expertise of the development team.
- Database software: a database management system to store and manage student and grading data.
- Web server software: to host the grading system and serve content to users.
- Testing software: automated testing tools to ensure the system is free of bugs and errors.
- Security software: firewalls, antivirus software, and other security measures to ensure the system is protected from cyber threats.
#### Other Expenses
- Licensing fees: some software components may require licensing fees.
- Training: training for staff members to ensure they are familiar with the system and can use it effectively.
- Maintenance and support: ongoing maintenance and support to ensure the system remains secure, updated, and functional.

### 10. Technical Specifications

#### Data Sources:
- Student data: including personal information, enrollment records, and academic performance data.
- Faculty data: including personal information, course schedules, and grading records.
- Course data: including course schedules, course descriptions, and prerequisites.

#### Data Schema:
- The data schema for the grading system would need to include tables for student information, course information, enrollment records, grading records, and other relevant data.

#### Data Transformations:
- Data transformations may be necessary to ensure the data is clean, consistent, and in the appropriate format for analysis. For example, data may need to be transformed to ensure it is compatible with the database management system being used.

#### Machine Learning Algorithms:
- Machine learning algorithms can be used to analyze student data and identify patterns and trends. For example, clustering algorithms could be used to group students based on their academic performance, while regression algorithms could be used to predict future grades.

#### Data Visualization Tools:
- Data visualization tools can be used to display grading data in a visually appealing and easily understandable format. For example, graphs and charts could be used to show the distribution of grades for a particular course or to compare the performance of different students.

#### Other Technical Details:

- Database Management System (DBMS): a robust database management system would be required to store and manage student and grading data.
- Web Development Framework: a web development framework would be used to build the front-end of the grading system.
- Server Infrastructure: a robust server infrastructure would be required to host the grading system and ensure it can handle large volumes of traffic.
- Security Measures: robust security measures would need to be in place to protect the system from cyber threats and ensure student data remains secure.

### Programming languages, Frameworks, and Libraries

#### Programming Languages:
- Java: Java is a widely used language with a large developer community and many resources available for learning and development. It is also well-suited for building robust and scalable systems.
- Python: Python is a versatile language that is well-suited for data analysis and machine learning. It also has a large number of libraries available for data manipulation, analysis, and visualization.
- PHP: PHP is a popular language for web development, and is often used in conjunction with databases to create dynamic and interactive websites.
#### Frameworks:
- Spring: Spring is a Java-based framework that provides a comprehensive platform for building robust and scalable web applications. It includes features such as dependency injection, data access, and web services.
- Django: Django is a Python-based web framework that is well-suited for building data-driven applications. It includes features such as an ORM, templating engine, and built-in admin interface.
- Laravel: Laravel is a PHP-based web framework that provides a comprehensive set of tools and features for building web applications.
#### Libraries:
- Pandas: Pandas is a Python library that provides data manipulation and analysis tools, including data structures for working with tabular data, time series, and more.
- Scikit-learn: Scikit-learn is a Python library for machine learning, providing tools for classification, regression, clustering, and more.
- Chart.js: Chart.js is a JavaScript library for creating interactive and customizable charts and graphs.


### Hardware and Software Requirements

#### Hardware Requirements:

- A server or a cluster of servers with adequate processing power and memory to handle a large number of concurrent users and perform data processing tasks.
- Storage devices, such as hard drives or solid-state drives, with enough capacity to store student data, course materials, and other relevant data.
- Network infrastructure, including routers, switches, and firewalls, to enable communication between the server and client devices.
#### Software Requirements:

- Operating System: The server should run on a stable and secure operating system, such as Linux or Windows Server.
- Database Management System (DBMS): A reliable and scalable database management system, such as MySQL or PostgreSQL, is required to store and manage student and grading data.
- Web Server: A web server, such as Apache or Nginx, is required to host the online grading system and serve web pages to clients.
- Programming Language and Framework: The choice of programming language and web development framework will depend on the specific needs and requirements of the project.
- Data Analysis Tools: If the system includes data analysis and machine learning capabilities, appropriate tools and libraries, such as Pandas and Scikit-learn, should be installed.
- Data Visualization Tools: Appropriate data visualization tools, such as Chart.js, should be installed to display grading data in a visually appealing and easily understandable format.


### Data Security Measures

- Encryption: All sensitive data should be encrypted both in transit and at rest. This means that data should be encrypted while it is being transmitted between the client and server, and also while it is stored in the database. Encryption helps to protect data from unauthorized access and theft.

- Access Controls: Access controls should be implemented to restrict access to student data only to authorized personnel. This includes implementing role-based access controls (RBAC), where users are granted access to only the data that they need to perform their job functions. Strong password policies should also be implemented to prevent unauthorized access.

- Secure Communication: All communication between the client and server should be conducted over secure channels, such as HTTPS, to prevent data interception and tampering.

- Regular Data Backups: Regular backups should be taken of the student data and stored in secure locations to ensure that data is not lost in case of a system failure or data corruption.

- System Monitoring: The system should be monitored regularly to detect any security breaches or unusual activity. This includes implementing intrusion detection systems, logging and auditing, and other monitoring tools to detect and respond to security threats.

- Regular Software Updates: Regular software updates should be performed to address any security vulnerabilities or bugs that may be present in the system.

- Employee Training: All employees who have access to student data should be trained on data security best practices, including password hygiene, secure communication, and access control.

By implementing these data security measures, the online grading system can ensure that student data is protected from unauthorized access, theft, and misuse.



### 11. Timeline and Deliverables: 
1. **Milestone 1: Project Planning and Requirements Gathering**
- Deadline: Week 1-2
<ul>Deliverables:

   - Project plan and timeline
   - Requirements document
   - Resource allocation plan</ul>
 
2. **Milestone 2: Data Collection and Preparation**
- Deadline: Week 3-4
<ul>Deliverables:
   
- Data sources identified and collected
- Data cleaning and preprocessing scripts
- Documented data schema</ul>
   
3. **Milestone 3: Data Analysis and Modeling**
- Deadline: Week 5-8
<ul>Deliverables:
   
- Exploratory data analysis report
- Machine learning models developed and trained
- Model validation and evaluation report</ul>

4. **Milestone 4: Data Visualization and Reporting**
- Deadline: Week 9-10
<ul>Deliverables:
   
   - Data visualization dashboards and reports
   - Final project report
   - Presentation slides
   - Quality Assurance and Testing Procedures:
      1. Code review and testing will be conducted throughout the development process to ensure high-quality code.
      2. Unit testing will be performed to verify the functionality of individual components.
      3. Integration testing will be conducted to test the integration of various components.
      4. User acceptance testing will be performed to ensure the system meets the requirements and is user-friendly.
      5. Automated testing scripts will be developed and executed to ensure the system is functioning as expected.
      6. Data quality assurance procedures will be implemented to ensure data accuracy and completeness.
      7. Security testing will be performed to identify and mitigate any security vulnerabilities.
      8. All deliverables will be reviewed and approved by the project stakeholders before being considered complete.
</ul>

### 12. Conclusion:
- The UTM Online Grading System is a much-needed solution to the challenges of the current manual grading system. By implementing an online platform, UTM can automate its grading processes, streamline communication between teachers and students, and enhance the overall learning experience. This proposed solution aligns with the university's goal of providing a modern and innovative education experience for its students.

- We understand that implementing such a system may come with some challenges, including resistance to change and technical difficulties. However, we are confident in our ability to deliver a high-quality system within the proposed timeline and budget.

- We urge the stakeholders to approve this proposal and take action towards the implementation of the UTM Online Grading System. With this system in place, UTM will enjoy improved efficiency, increased accuracy, and enhanced transparency in grading processes. We believe that this project will have a significant positive impact on the university, its teachers, and students.
