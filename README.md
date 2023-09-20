# Employee-Database-Management-System-Using-JDBC

## Description
This Java program is a simple Employee Database Management System that allows users to perform basic CRUD (Create, Read, Update, Delete) operations on an employee database stored in a MySQL database. It provides a text-based menu-driven interface for users to interact with the database.

## Features
- Insert a new employee record with employee number, name, and age.
- Delete an existing employee record by specifying the employee number.
- Modify an employee's name by specifying the employee number.
- Display a list of all employee records in the database.

## Requirements
- Java Development Kit (JDK)
- MySQL database
- MySQL Connector/J library (included as a dependency in the code)

## Usage
1. Clone the repository to your local machine.
2. Make sure you have a MySQL database set up and running.
3. Configure the database connection details (URL, username, and password) in the code by modifying the `getConnection` method.
4. Compile and run the `Temp2.java` file.

## Database Configuration
Make sure to configure the following lines in the code with your MySQL database connection details:

```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/employee1?characterEncoding=latin1", "root", "your_password_here");

