# Requirement Analysis in Software Development.
Requirement Analysis in Software Development.
This repository is dedicated to Requirement Analysis in Software Development. It serves as a structured space to document, organize, and analyze software requirements, covering activities such as requirement gathering, modeling, and validation. The goal is to provide clarity between stakeholders and developers, ensuring that the system’s functional and non-functional needs are well understood before moving into design and implementation.
# What is Requirement Analysis?
Requirement Analysis is a crucial phase in the Software Development Lifecycle (SDLC) where the needs and expectations of stakeholders (clients, end-users, and business teams) are identified, analyzed, documented, and validated. It is the foundation of any software project because it defines what the system should do before moving into how it will be built.

In this phase, business analysts, project managers, and developers collaborate with stakeholders to gather requirements through techniques such as interviews, surveys, workshops, document reviews, and observations. These requirements are then modeled using tools like use case diagrams, data flow diagrams, and user stories to provide a clear picture of the system’s functionality.


# Why is Requirement Analysis Important?
Clarity & Alignment → It creates a shared understanding between stakeholders and the development team, reducing miscommunication.

Cost & Time Efficiency → Detecting errors or missing requirements early is cheaper than fixing them later in design or coding.

Quality Assurance → Well-defined requirements ensure the final product meets user needs and business objectives.

Risk Reduction → Identifying potential issues early lowers the chances of project failure.

Better Planning → Clear requirements help in accurate project estimation (time, budget, resources).

In short, requirement analysis acts as the blueprint of the software project. Without it, development risks drifting away from stakeholder expectations, leading to wasted effort, cost overruns, and unsatisfied users.
# Key Activities in Requirement Analysis
1. Requirement Gathering

This is the initial step where raw requirements are collected from stakeholders such as clients, end-users, managers, or external systems. The focus is on understanding what the stakeholders want from the system. Common techniques include brainstorming sessions, questionnaires, observations, and reviewing existing documents.

2. Requirement Elicitation

Elicitation goes beyond simple collection — it’s about actively engaging stakeholders to uncover hidden, unclear, or conflicting requirements. It involves interviews, workshops, prototyping, and use cases to make sure nothing important is overlooked. The goal is to capture both functional requirements (what the system does) and non-functional requirements (performance, security, usability, etc.).

3. Requirement Documentation

Once gathered and elicited, requirements must be clearly documented in a structured format that both technical and non-technical stakeholders can understand. This may include Software Requirement Specifications (SRS), user stories, or visual diagrams. Documentation serves as a reference point for the entire SDLC and ensures traceability throughout development.

4. Requirement Analysis and Modeling

Here, the requirements are analyzed, refined, and prioritized. The objective is to resolve conflicts, remove ambiguities, and check feasibility. Modeling techniques such as use case diagrams, data flow diagrams, class diagrams, and prototypes are used to represent requirements visually, making them easier to understand for both developers and stakeholders.

5. Requirement Validation

This final activity ensures that all documented requirements are complete, consistent, testable, and aligned with business objectives. Validation is done through reviews, walkthroughs, stakeholder feedback sessions, and prototyping. It reduces the risk of building the wrong product by confirming that the captured requirements truly reflect stakeholder needs.
# Types of Requirements
-Functional Requirements (What the system should do)

These are the features and services the system must provide.

Examples from the case study:

@ User & Hotel Management

Customers can create accounts, log in, and update profiles.

Hotel managers can add, update, and delete hotel listings (rooms, prices, availability).

@ Search & Booking

Customers can search hotels by location, date, price, and rating.

Customers can book rooms and receive booking confirmation.

Customers can cancel or modify bookings.

@ Payment & Transactions

Integration with third-party payment gateways (Stripe, PayPal, etc.).

Support for refund processing in case of cancellations.

@ Notifications

Send booking confirmations to customers via email/notification.

Notify hotel managers when a new booking is made.

@ View Bookings

Customers can view current and past bookings.

Managers can view all bookings related to their hotels.

-Non-functional Requirements (How the system should perform)

These describe the quality attributes of the system.

Examples from the case study:

@ Performance & Scalability

The system should handle thousands of concurrent searches and bookings.

Search results should load in under 2 seconds even during peak traffic.

Support horizontal scaling with microservices architecture.

@ Reliability & Availability

The system must have 99.9% uptime to support global users.

Booking operations must be transactional (no double-booking).

@ Security

Payment processing must comply with PCI-DSS standards.

All sensitive data (passwords, payment info) must be encrypted.

Users must be authenticated securely with JWT or OAuth.

@ Usability

The app must be user-friendly, supporting multi-language and multi-currency.

Provide responsive design for mobile and web users.

@ Maintainability & Extensibility

The system should be designed with modular microservices for easier updates.

# Use Case Diagrams
Use case diagrams (part of UML) show how users (actors) interact with a system by visualizing the system’s functional requirements as use cases (ovals). They’re like a quick map of “who does what” — perfect for aligning stakeholders, scoping features, and guiding test cases.

Benefits

Clear stakeholder communication (non-tech folks love these).

Quick scoping: shows system boundary and what’s inside/outside scope.

Helps derive user stories / acceptance criteria.

Great for validating that all user journeys are covered.

Useful reference for designers, devs, and QA.

https://drive.google.com/file/d/alx-booking-uc/view?usp=sharing



New services (like loyalty programs or discount coupons) can be added without disrupting core booking.
