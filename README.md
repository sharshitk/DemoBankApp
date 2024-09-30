# DemoBankApp
The Bank Application is a Java-based software system designed to manage customer accounts and financial transactions in a banking environment. 
It provides a user-friendly graphical interface that enables users to perform a variety of banking operations, such as opening and closing accounts, depositing and withdrawing funds, and viewing account details. 
The application integrates with a MySQL database for persistent data storage.

# Key Features

**Account Management**

Users can open new accounts (checking and savings), close existing accounts, and manage account details.
Each account is associated with a unique account number and tracks the balance.

**Customer Management**

The application allows for the registration of customer details, including first name, last name, and Social Security Number (SSN).
Customer information is displayed alongside their account details in a table format.

**Transactions**

Users can perform deposits and withdrawals, with built-in transaction fees depending on the account type.
The application automatically calculates interest on deposits based on account balance thresholds.

**Data Persistence**

Utilizes a MySQL database to store customer and account information securely.
CRUD (Create, Read, Update, Delete) operations are implemented to manage account records in the database.

**User Interface**

Built using Java Swing, the GUI is intuitive and easy to navigate.
The main menu provides buttons for various operations, along with a table displaying account information for quick access.

**Error Handling**

The application incorporates error handling for scenarios like insufficient funds during withdrawals and invalid amounts during deposits.

**Programming Language:** Java

**Database:** MySQL

**GUI Framework:** Java Swing

**Development Environment:** Apache NetBeans18

# Installation and Setup

Set up a MySQL database and create the necessary tables (Users, Accounts, Mappings).

Configure the database connection details in the DbService class.

Compile and run the application in a Java-supported environment.

# Conclusion

The Bank Application offers a comprehensive solution for basic banking operations, combining effective account management with a user-friendly interface. It demonstrates key software engineering principles such as modular design, data encapsulation, and interaction with relational databases. This project serves as a practical example for understanding object-oriented programming and database integration in Java.


