# Java JDBC – Employee Database App

## Objective
A Java application that connects to a PostgreSQL database using JDBC to perform **CRUD** (Create, Read, Update, Delete) operations on an Employee table.

---

## Features
- **Add Employee** – Insert a new employee into the database.
- **View Employees** – Display all employee records.
- **Update Employee** – Modify existing employee details.
- **Delete Employee** – Remove an employee from the database.
- **Menu-driven console application** for easy interaction.

---

## Tools & Technologies
- **Java** (JDK 8+)
- **PostgreSQL**
- **JDBC** API
- **PostgreSQL JDBC Driver** (e.g., `postgresql-42.7.3.jar`)
- IDE: **Eclipse / IntelliJ IDEA**

---

## Database Setup

1. Open **PostgreSQL** and create the database:
    ```sql
    CREATE DATABASE Demo;
    ```

2. Connect to the database:
    ```sql
    \c Demo
    ```

3. Create the `employees` table:
    ```sql
    CREATE TABLE employees (
        id SERIAL PRIMARY KEY,
        name VARCHAR(100) NOT NULL,
        department VARCHAR(100),
        salary NUMERIC(10,2)
    );
    ```

---

## Project Structure
