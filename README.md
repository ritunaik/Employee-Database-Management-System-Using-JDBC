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

## Tools Used:
Java: The core programming language used to build the application.
MySQL: The relational database management system used to store and manage employee records.
JDBC (Java Database Connectivity): A Java-based API for connecting to and interacting with databases.
Git: Version control system for tracking changes in the project.
GitHub: Hosting platform for sharing and collaborating on code.

## How to Use:
Clone the repository:
git clone <repository-url>

## Compile the Java program:
javac exp2/Temp2.java

## Run the program:
java exp2.Temp2

## Contributing:
If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. We welcome contributions and improvements.

## Issues:
If you encounter any issues or have suggestions for improvements, please open an issue on this repository, and we'll look into it.

## Usage
1. Clone the repository to your local machine.
2. Make sure you have a MySQL database set up and running.
3. Configure the database connection details (URL, username, and password) in the code by modifying the `getConnection` method.
4. Compile and run the `Temp2.java` file.

## Database Configuration
Make sure to configure the following lines in the code with your MySQL database connection details:

```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/employee1?characterEncoding=latin1", "root", "your_password_here");



