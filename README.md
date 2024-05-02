# Description

The Banking Application Project includes the development of a comprehensive banking system, tailored to accommodate both customers and administrators. This project, leveraging the Spring Boot framework for backend operations and React for the frontend, will provide users with a streamlined management tool to effectively oversee their accounts. The primary objective of this banking system is to deliver a robust platform that meets the diverse needs of both users and administrators while prioritizing security and efficiency

## Technical Requirements
- Build the application at least Java 17 and Spring Boot 3

- All interactions between a User and the API should happen via HTTP Requests. Using a tool like Postman will allow you to set up these requests.

- All data should be stored in PostgreSQL Database to persistance our data

    - As a user, I should be able to create my account
    - As a user, I should be able to login into my account
    - As a user, I should be able to make withdrawals/deposits
    - As a user, I should be able to check my checking/savings accounts
    - As a user, I should be able to transfer money between my accounts
    - As a user, I should be able to transfer money to other people
    - As a admin, I should be able to create my account
    - As a admin, I should be able to view all user accounts
    - As a admin, I should be able to view all accounts associated to each user
    - As a admin, I should be able to reset a user account password
    - As a admin, I should be able to lock/unlock a user account
    - As a admin, I should be able to enable/disable an account(checking/savings) associated to a user

- **NOTE** Responses from the API must include proper response bodies (in JSON) and **status codes**
