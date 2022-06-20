# project-1
Guidelines and requirements for Project 1

> ERS, or Employee Reimbursement System, is a full-stack web application that allows employees to submit requests for reimbursements for courses, events, and certifications. These requests can then be approved or rejected by the Finance Manager, while the employee is able to track the status of their requests.
You will be required to present a 5-10 minute demo of your application and its features.

## Purpose
The main purpose of this project is to have you work with Testing AUtomation using Selenium and Cucumber.

### Presentation date: Friday, July 1, 2022

## Requirements
- All required business rules from the [Project1 ERS.docx](https://github.com/220531-jwa/project-1/blob/main/Project1%20ERS.docx) must be implemented.  
  - (The ability for an employee to upload a document can be considered a stretch goal along with the other business rules below under Stretch Goals).
- All application data must be stored in an RDS.
  - Database must be in 3NF. 
- Your application should be as RESTful as possible (at minimum it must follow the restful endpoint naming conventions).
- You must write BDD tests using Cucumber and Selenium for all user stories. 

- Project must also have:
  - Logging.
  - User input validation.
  - Unit Tests - goal of 70% test coverage
  - Styled web pages either with CSS or Bootstrap. (Don't go overboard).

## Stretch Goals
- Ability to upload attachments
- Finance Manager can request additional information
- Employee can cancel the reimbursement request if the reimbursable amount is changed by the Finance Manager
- Auto-approval after a certain period of time
- Available reimbursement resets on the new year

## Tech Stack
- Java 8
- Apache Maven
- Selenium
- Cucumber
- Apache Log4j 2
- PostgreSQL
- AWS RDS
- Javalin
- JUnit
- JDBC 
- JavaScript
- AJAX / Fetch API
- HTML
- CSS / Bootstrap
