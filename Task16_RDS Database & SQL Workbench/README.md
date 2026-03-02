# RDS Database & SQL Workbench

## Project Overview
This project demonstrates creating an Amazon RDS managed relational database, connecting to it using SQL Workbench, and executing basic SQL queries.

## Objective
- Launch a managed RDS instance.
- Connect from SQL Workbench to perform database operations.
- Learn basic SQL queries and RDS management.

## Steps
1. Launch an **RDS instance** (e.g., MySQL or PostgreSQL):
   - Configure VPC, security groups, and database credentials.
2. Install **SQL Workbench** and set up a connection to the RDS endpoint.
3. Test the connection and execute basic SQL commands:
   ```sql
   CREATE DATABASE testdb;
   CREATE TABLE employees (id INT PRIMARY KEY, name VARCHAR(50));
   INSERT INTO employees VALUES (1, 'Aniket');
   SELECT * FROM employees;