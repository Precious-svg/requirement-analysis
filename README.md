# requirement-analysis
Describes software development lifecycle 

## Requirement Analysis in Software Development.
 This involves outlining and understanding the requirements and goals of a stakeholder and the needs of users in the devloment of a software product. THis is the documentation of the purpose, importance, crucial features and contsraints of product. This is written in an official document which then serves as blue print for the design and develpment of the product.
 

## Why is Requirement Analysis Important
**1. Foundation of the design and development**: The analysis and documentation of user needs and crucila feature in simple clear and easily understanble terms serve as the pattern and foundation on which the design of the product is built. This helps to reduce the risk or totally eliminate the need to revise and redo the design at a later stage.

**2. Reduces the risks if bugs and errors**: Proper requirement analysis helps to identify errors, constraints and mission functionality early in the stage. It also helps to prevent working against the scope provided. This helps to reduce the cost incurred with late stage revisions and corrections.

**3. Stakeholders collaboration and satisfaction**: This facilitates communication between stakeholders and promtes alignment by making sure that everyone agrees on what the product is meant  to do. Thereby ensuring that user needs are met and that stakeholders are satisfied with the outcome. 


## Key Activities in Requirement Analysis
This involves a series of steps that maps out and documents wha the key stakeholder want or expect from a software, they are listed below:

- ***Requirement Gathering***: 
  - This is the very first step and it involves extensive data research and compiltaion. Information is gotten from the stakeholders, users, users and market research.

- ***Requirement Elicitation***: 
   - Uses data gathering and research methods such as surveys and interviews to gather more detailed and implicit requirments.
   - This aims and clarifying expectations beyond the surface level.
   
- ***Requirement Documentation***:
   - This involves structruring th einformation and requirements gathered into a traceable and formal documenation such as user stories or software requirement specifications.
   - This ensures clear, traceable and consistent communication between memebers involved in the project.
   
- ***Requirement Analysis and Modeling***:
    - This involves analysis and reviewing the documentation to identify for any gaps, redundancy or conflicts.
    - Using modeling techniques to visualise and better understand system relationship and behaviours.
    
- ***Requirement Validation***:
    - Here the requirements are reviewed with the stakeholders to validate is accuracy, completeness and feasibility.
    - This aims at ensuring that the document truly reflects what is needed and within the constraints.


## Types of Requirements

### Subsection one

#### ***Examples of Functional Requirements***

- User Authentication: The system must allow users to register, log in, and log out securely.
- Booking Creation: Users should be able to create a new booking by selecting available time slots, services, and resources (e.g., rooms or equipment).
- View Bookings: Users and administrators must be able to view upcoming and past bookings.
- Admin Dashboard: Administrators should be able to manage user accounts, review all bookings, and generate usage reports.

### ***Examples of Non-Functional Requirements***

- Performance: The system should process booking requests within 2 seconds under normal load conditions.
- Scalability: The application must support up to 10,000 concurrent users without performance degradation.
- Usability: The interface should be intuitive and responsive, with mobile and desktop compatibility.
- Security: All data must be encrypted in transit and at rest, and user sessions should automatically expire after 15 minutes of inactivity.

## Use Case Diagrams
 ***What Are Use Case Diagrams?***
      Use case diagrams are a type of Unified Modeling Language (UML) diagram that visually represent the interactions between users (actors) and a system. They provide a high-level 
      overview of the system's functionalities and how different users engage with them. Each use case illustrates a specific goal or task that an actor aims to achieve within the 
      system.

 ***Benefits of Use Case Diagrams***
 
   - Clarify System Requirements: They help in identifying and defining the functional requirements of the system by illustrating user interactions.

   - Enhance Communication: Serve as a communication tool between stakeholders, developers, and users to ensure a shared understanding of system functionalities.

   - Aid in System Design: Provide a foundation for designing the system architecture and user interfaces by outlining key interactions.

   - Support Testing and Validation: Assist in creating test cases by highlighting the expected behaviors and interactions within the system.

##Acceptance Criteria
 ***Importance of Accepatnce criteria***: 
    Acceptance requirement is the criteria that a product was meet to be accepte by stakeholders, this is usualluy defiend during the requirement analysis phase.
    It is important because it reduce sthe rsik of scope creep, it serves as the basis on which test can be carried out to determine if the product behavse as expected.

 ###Example of Acceptance Crietria for the Checkout feature in a booking managememt system###
  - User must be logged in to proceed to payment.
  - The checkout page should show a summary of the booking information.
  - The system should allow users to select payment method such as debit, credit or apple pay.
  - On successful payment and transaction, a confirmation mail with the receipt should be sent to the user email.
  - If payment ad tarnsaction is successfull or did not go through the page should display this information appropraitely.

    To be c
