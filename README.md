# Hospital Management System

This is a console-based Hospital Management System developed using Java and JDBC.
The project demonstrates how to integrate Java applications with a relational database to manage hospital-related data such as patients, doctors, and appointments.

---

## Tech Stack

Language: Java

Database: MySQL

Database Connectivity: JDBC

IDE: IntelliJ IDEA / Eclipse

Project Type: Core Java

---

## Features

Add and view patient details

Add and view doctor details

Book appointments

Check doctor availability by date

Data persistence using MySQL

Proper use of primary keys and foreign key relationships

---

## Database Schema

The system uses the following tables:

patients

doctors

appointments

Foreign keys are used to maintain relationships between doctors, patients, and appointments.

--- 

## How to Run the Project

1. **Clone the repository**

   git clone https://github.com/your-username/hospital-management-system.git
   
2. **Open the project in IntelliJ IDEA or Eclipse**

3. **Create the database in MySQL**

  CREATE DATABASE hospital_db;

4. Run the SQL script provided in the database/ folder to create tables
  
5. Update database credentials in the JDBC connection class

   String url = "jdbc:mysql://localhost:3306/hospital_db";
   
   String username = "root";
   
   String password = "your_password";

7. Run the main class to start the application

---

## What This Project Demonstrates

JDBC connection handling

SQL queries executed from Java

CRUD operations

Backend logic implementation

Relational database design

--- 

## Future Enhancements

GUI using JavaFX or Swing

Login and role-based access

Better exception handling and validations

REST API using Spring Boot

