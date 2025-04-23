# Homestay-App
This document describes the testing approach for the homestay booking  platform, which serves three distinct user roles: Guests, Caretakers, and  House Owners. The platform enables guest registration with OTP  verification, homestay booking, real-time notifications, and administrative  oversight. 


1.1 Overview: 
This document describes the testing approach for the homestay booking 
platform, which serves three distinct user roles: Guests, Caretakers, and 
House Owners. The platform enables guest registration with OTP 
verification, homestay booking, real-time notifications, and administrative 
oversight. 
1.2 Purpose & Objectives: 
● Purpose: To ensure the system meets functional and non-functional 
requirements. 
● Objectives: 
○ Verify each module (registration, OTP verification, login, 
booking, SMS alerts, and booking management) functions as 
intended. 
○ Confirm that data validations (e.g., proper phone number 
format, OTP timeouts) are enforced. 
○ Validate the overall usability and responsiveness of the web 
application. 
1.3 Scope: 
○ Guest Module: User sign-up, OTP verification, viewing 
available homestay dates, booking, SMS notifications, and 
booking modifications or cancellations. 
○ Caretaker Module: OTP-based login, managing and viewing 
bookings, updating identity proofs and payment details, and 
processing checkouts with guest feedback. 
○ House Owner Module: OTP-based login, overview of all 
bookings, and access to detailed booking information including 
guest credentials. 
○ 1.4 Methodology: 
○ Primarily manual testing,  
1.5 Test Environment: 
● A staging environment that closely mirrors production settings. 
● Simulated SMS gateway responses for verifying notification delivery. 
● Predefined test user accounts for each user type. 
1.6 Roles & Responsibilities: 
● Test Lead/Manager: Oversees test activities and final reporting. 
● QA Engineers: Develop and execute test cases, record outcomes, 
and log defects. 
● Development Team: Address defects and support re-testing efforts. 
1.7 Schedule and Deliverables: 
● Timeline: Defined by sprint cycles and overall project deadlines. 
● Deliverables: 
○ Testing Strategy Document (this document) 
○ Detailed Test Scenario Document 
○ Test Case Log in Excel/CSV format 
○ Execution Reports and Defect Logs 
1.8 Risks & Mitigation: 
● Risks: 
○ Potential delays from third-party SMS services. 
○ Data inconsistencies due to concurrent booking attempts. 
● Mitigation Strategies: 
○ Use SMS simulation for early tests. 
○ Design test cases to cover concurrent booking scenarios 
thoroughly.
