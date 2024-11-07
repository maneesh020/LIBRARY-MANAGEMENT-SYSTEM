# LIBRARY-MANAGEMENT-SYSTEM
Library Management System (LMS)
This Library Management System project is built to keep track of books, customers, employees, and transactions (issuing and returning books) within a library. It includes SQL tables for each entity and SQL queries for common library operations.

Database Schema
The LMS database includes the following tables:

Branch - Information about library branches.
Employee - Details of employees, linked to their respective branches.
Books - Data about each book, including availability status and rental price.
Customer - Information about library members.
IssueStatus - Records of issued books.
ReturnStatus - Records of returned books.
Key SQL Queries
Sample queries included in the project:

Available Books - Retrieve title, category, and rental price.
Employee Salaries - List employees by salary in descending order.
Issued Books - List book titles with corresponding customers.
Books by Category - Count of books in each category.
High-Salary Employees - Employees with salaries over Rs.50,000.
Non-Issuing Customers - Customers registered before 2022 who haven’t issued books.
Branch Employee Counts - Total employees in each branch.
Customers in June 2023 - Customers who issued books in June 2023.
History Books - Retrieve titles containing "history".
Branches with Many Employees - Branches with more than 5 employees.
Branch Managers - Names of managers and their branch addresses.
High-Rent Books - Customers who issued books with rental prices above Rs.25.

Project Setup
Create Database: Execute the SQL code to set up the database and tables.
Insert Data: Add sample data to test queries.
Run Queries: Use the provided queries for each operation, and capture results in screenshots.
Submission
Upload the SQL code and screenshots folder to GitHub.
