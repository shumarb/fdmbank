# FDM Bank

## Overview
FDMBank is an online banking platform for customers to manage their finances via multiple bank accounts and credit cards, as well as redeeming gifts based on points accrued.

## Tech Stack
- Programming: Java.
- Frameworks/Tools:
    - Spring Boot.
    - Spring Security.
    - Spring Data JPA.
    - Lombok.
    - MySQL.
    - Thymeleaf.
    - Mockito.
    - JUnit.
    - Git.
    - HTML/CSS.

## Prerequisites
- Java 17.
- Git.
- IntelliJ IDEA.
- MySQL, and MySQL Workbench.

## Setup
1. `Clone` this repository.
2. Open the `IntelliJ IDE`.
3. Ensure you have installed the `lombok` plugin on `IntelliJ IDE` for compatibility with the application.
4. Select `Open` and navigate to the location of the cloned repository.
5. Create a `schema` on the MySQL Workbench.
6. Update `application.properties` in the `src/main/resources` folder:
    - Line 5: Set `spring.datasource.url=jdbc:mysql://localhost:3306/name-of-your-schema`.
    - Line 6: Set `spring.datasource.username=name-of-your-mysql-username`.
    - Line 7: Set `spring.datasource.username=name-of-your-mysql-password`.

## Instructions
1. Open the `terminal` of your local machine.
2. Navigate to the location of the cloned repository.
3. Run `git pull origin main` to ensure you have the latest version of the repository.
4. Right-click the `CreditCardProjectApplication` class file (Location: `src/main/java/com/example/fdmgroup/CreditCardProjectApplication.java`).
5. Select `Run 'CreditCardProj....main()`.
6. If there are issues with running the application, perform the following before repeating Step 1:
    - Click the `Maven icon` on the right.
    - Navigate to `CreditCardProject/Lifecycle`.
    - Click `Clean`, then `Install`.
    - Drop all tables in the schema.
    - Close and reopen IntelliJ IDEA.
7. Enter `localhost:9001/` in your browser after seeing the message `Started CreditCardProjectApplication...` in the `console`.
8. Explore the application and examine data in the MySQL Workbench.
