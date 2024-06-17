[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248253&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software engineering is an application of systematic, disciplined and quantifiable approaches to the development, operation and maintenance of software.

What is software engineering, and how does it differ from traditional programming?
Software engineering is an application of a systematic, disciplined and quantifiable approach to the development, operation and maintenance of software. On the other hand, traditional programming is focused on writing code and solving a certain problem at hand. It focuses on the development of software.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
This life cycle is used by project teams to ensure the delivery of high-quality and efficient software, the steps are as follows:
REQUIREMENT ANALYSIS AND SPECIFICATION: Its purpose is to identify and document the requirements of the proposed system.
PLANNING: The scope of the project is determined, resources and risks.
DESIGN: It focuses on how the project will be done by creating the architecture of the system.
IMPLEMENTATION: The actual code of the program is written according to the architecture of the design phase.
        TESTING: The system is executed to find out errors and non-compliance.
        DEPLOYMENT: The system is delivered to the users to ensure that it is operational.
        MAINTENANCE: It is concerned with modifying the system to correct faults, improve performance and adapt to the changing environment.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
The agile model uses an iterative and flexible approach, divides work into time-based sprints and prioritizes delivering value whereas the waterfall model uses a linear and sequential approach, the stages are well-defined and the requirements are completed before moving to the next phase
The key differences are that the agile model prioritizes flexibility and rapid value delivery while the waterfall model provides for stability and predictability.
A scenario in agile models is large-scale projects with stable requirements and require predictability. The waterfall model is used in cases of dynamic or changing environments and where the project has evolving requirements.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements engineering is the task of capturing, structuring and accurately representing the user's requirements so that they can be correctly embodied in the system which meets those requirements.
Process of requirement engineering:
FEASIBILITY STUDY: A feasibility study decides whether or not the proposed system contributes to the organisational objectives,  can be engineered using current technology within a budget and if the system can be integrated with other systems that are used.
REQUIREMENT ELICITATION: It is the action of discovering system requirements through consultation with stakeholders. Some of the sources of this discovery could be system documents, domain knowledge, and market studies. 
REQUIREMENT ANALYSIS: It is scrutinizing the gathered requirements in order to make consistent and unambiguous requirements. It also involves providing a graphical view of the system using the requirements. This is done by the use of a context diagram and Data Flow Diagram(DFD)
REQUIREMENT SPECIFICATION: The gathered requirements are documented in detail.
REQUIREMENT VALIDATION: It is the process of reviewing requirements for clarity, consistency and completeness. 
REQUIREMENTS MANAGEMENT: Requirements management is the process of managing changing requirements during the requirements engineering process and system development.
Requirements engineering helps software engineers to better understand the problem they will work to solve.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve the maintainability and scalability of software systems?
Modularity is a concept used to create software that reduces dependencies on the components of a software system.
It improves maintainability in that when one part of the software is changed, it does not affect others making it easy to fix bugs and improves scalability in the sense that when a module is enhanced or a new one is added, it does not affect the rest of the software system.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
UNIT TESTING is a level of software testing where individual units/ components of software are tested. The purpose is to validate that each unit of the software performs as designed.
INTEGRATION TESTING is a level of software testing where individual units are combined and tested as a group. The purpose of this level of testing is to expose faults in the interaction between integrated units.
SYSTEM TESTING is a level of software testing that tests a system as a whole. Its purpose is to test end-to-end functionality including user interfaces, databases and external integrations.
ACCEPTANCE TESTING is a level of software testing where a system is tested for acceptability. The purpose of this test is to evaluate the system’s compliance with the business requirements and assess whether it is acceptable for delivery.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
VCS are software development tools that manage changes in source code
Importance of VCS:
COLLABORATION: It allows multiple developers to work simultaneously, preserving each person’s changes and preventing conflicts on a given project.
TRACKS HISTORY: It maintains a detailed account of code modifications, making changes trackable and reversible.
RELEASE MANAGEMENT: Facilitates maintaining different software versions for various customers.
Examples of VCS include;
GIT.Features: Branching, merging, history visualization, and collaboration.
SUBVERSION.Features: Versioned directories, atomic commits, and access control.
PERFORCE.Features: High performance, fine-grained access control, and asset management.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Project Managers Plan, Monitor and Control the work of a Team of Software Engineers.
Key responsibilities of project managers include:
        -Project planning 
        -Project execution and monitoring
        -Risk management
        -Team coordination
        -Quality assurance
Challenges faced by software project managers
        -Changing requirements
        -Limited resources
        -Technical complexity
        -Communication with various stakeholders can be tiresome.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Software maintenance is the process of modifying a software system or component after delivery to correct faults, improve performances or other attributes, or adapt to a changed environment.

The different types of maintenance activities include:
CORRECTIVE MAINTENANCE: It includes all the changes made to remove actual faults in the software. 
ADAPTIVE MAINTENANCE: It encompasses the changes needed as a consequence of some mutation in the environment in which the system must operate, for instance, altering a system to make it run on a new hardware platform, operating system, DBMS, TP monitor, or network. 
PERFECTIVE MAINTENANCE: It refers to changes that originate from user requests; examples include inserting, deleting, extending, and modifying functions, rewriting documentation, improving performances, or improving ease of use. 

Maintenance aims to keep the artefact’s functionality in line with that defined and registered at the time of release.


Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Algorithmic bias - Biased algorithms can perpetuate discrimination based on race, gender, or other factors:
    Adherence:
    Awareness - Understand bias risks in your algorithms.
    Fairness - Regularly audit and mitigate bias.
    Inclusivity - Involve diverse teams during development.
 Data privacy - Mishadling user data violates data privacy
    Adherence:
    Consent - Obtain informed consent for data collection.
    Encryption - Protect sensitive data.
    Compliance - Follow privacy regulations (e.g., GDPR).
Security vulnerability - Ignoring security risks can lead to data breaches.
     Adherence:
     Secure Coding - Follow best practices (e.g., input validation, secure APIs).
     Testing - Regularly test for vulnerabilities.
     Patch Management - Keep software up-to-date.

Reference:
Wikipedia contributors. (2024, May 19). Systems development life cycle. Wikipedia. https://en.wikipedia.org/wiki/Systems_development_life_cycle
Agile vs. Waterfall. (2021, August 26). Pros, Cons, and Key Differences. https://www.productplan.com/learn/agile-vs-waterfall/
https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/
Online, I. (2024, April 21). What is modularity in software design? - ITU Online. ITU Online IT Training. https://www.ituonline.com/tech-definitions/what-is-modularity-in-software-design/#:~:text=Modularity%20is%20a%20fundamental%20design,the%20understandability%20of%20the%20system.
Rao, A. (2023, December 14). What is version control? Definition, types, systems and tools - LogRocket Blog. LogRocket Blog. https://blog.logrocket.com/product-management/version-control-systems-definition-types/
    
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
