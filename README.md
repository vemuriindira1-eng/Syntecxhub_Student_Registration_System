# Student Registration System

## Project Overview
The Student Registration System is a Java-based application developed using JDBC and MySQL. It helps manage student information by allowing users to register, view, update, and delete student records.

## Features
- Register new students
- Display all registered students
- Update student details
- Delete student records
- Store student information in a MySQL database
- Use JDBC to connect Java with MySQL
- Use PreparedStatement for secure database operations

## Technologies Used
- Java
- JDBC
- MySQL
- MySQL Connector/J
- Visual Studio Code

## Database Details
**Database Name:** `student_db`

**Table Name:** `students`

| Column | Data Type |
|---|---|
| student_id | INT (Primary Key, Auto Increment) |
| name | VARCHAR(100) |
| email | VARCHAR(100) |
| phone | VARCHAR(15) |
| course | VARCHAR(100) |
| age | INT |

## Project Structure

```text
StudentRegistrationSystem/
├── lib/
│   └── mysql-connector-j-26.10.0.jar
├── StudentRegistration.java
└── README.md
```

## How to Run the Project

1. Install Java JDK and MySQL.
2. Create a database named `student_db`.
3. Create the `students` table.
4. Add MySQL Connector/J to the `lib` folder.
5. Set your MySQL password as the `DB_PASSWORD` environment variable.
6. Open the project folder in the terminal.
7. Compile the Java program:

```powershell
javac -cp ".;lib\*" StudentRegistration.java
```

8. Run the program:

```powershell
java -cp ".;lib\*" StudentRegistration
```

## Database Security
The MySQL password is read from an environment variable instead of being stored directly in the Java source code.

## Internship Project
**Organization:** Syntecxhub  
**Project:** Student Registration System  
**Domain:** Java Programming