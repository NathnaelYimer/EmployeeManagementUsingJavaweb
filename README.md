# Simple Employee Management System

This is a basic Employee Management System implemented using Java servlets, JDBC, and Apache Tomcat.

## Table of Contents

- [Features](#features)
- [Database Setup](#database-setup)
- [Servlets](#servlets)
- [Forms](#forms)
- [JDBC](#jdbc)
- [Apache Tomcat](#apache-tomcat)
- [Testing](#testing)
- [Project Structure](#project-structure)

## Features

- **Database Setup:**
  - MySQL database with an `employees` table.
  - Table columns: `id`, `name`, `designation`, `salary`.

- **Servlets:**
  - `AddEmployeeServlet`: Add a new employee to the database.
  - `ViewEmployeesServlet`: Display all employees in a tabular format.
  - `EditEmployeeServlet`: Edit an existing employee in the database.
  - `DeleteEmployeeServlet`: Delete an employee from the database.

- **Forms:**
  - HTML forms for adding and editing employees.
  - Input fields for `name`, `designation`, and `salary`.

- **JDBC:**
  - Interact with the MySQL database using JDBC.
  - Methods for connecting to the database, executing SQL queries, and handling CRUD operations.

- **Apache Tomcat:**
  - Deployment of the application on Apache Tomcat.
  - Portable database connection configuration.

- **Testing:**
  - Manual testing of CRUD operations.
  - Testing error scenarios, such as submitting forms with invalid data.

## Database Setup

1. Set up a MySQL database.
2. Create a table named `employees` with columns: `id`, `name`, `designation`, `salary`.

## Servlets

- **AddEmployeeServlet:**
  - Display a form to add a new employee.
  - Process form data and insert a new employee into the database.

- **ViewEmployeesServlet:**
  - Retrieve all employees from the database.
  - Display them in a tabular format.

- **EditEmployeeServlet:**
  - Display a form to edit an existing employee.
  - Process form data and update the employee in the database.

- **DeleteEmployeeServlet:**
  - Delete an employee from the database.

## Forms

- HTML forms for adding and editing employees.
- Input fields for `name`, `designation`, and `salary`.

## JDBC

- Use JDBC to interact with the MySQL database.
- Implement methods for connecting to the database, executing SQL queries, and handling CRUD operations.

## Apache Tomcat

- Deploy the application on Apache Tomcat.
- Configure the database connection to be portable between different environments.

## Testing

- Manually test each CRUD operation to ensure they work as expected.
- Test error scenarios, such as submitting forms with invalid data.

## Project Structure

