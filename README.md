My SQL Tutorial

About This Repository

This repository contains my notes, practice queries, and key lessons as I learn SQL from scratch. I'm documenting my progress one step at a time, correcting my mistakes, and building a solid foundation in data analysis and cybersecurity.

What I've Learned So Far

- Using "SELECT" to retrieve specific columns from a database.
- Using "FROM" to specify the table containing the data.
- Using "WHERE" to filter records based on a condition.
- Performing basic arithmetic operations in SQL.
- Understanding how SQL queries are structured.

Corrected SQL Queries

1. Selecting Specific Employee Information

SELECT first_name, last_name, birth_date, age, age + 10
FROM Eve_and_jay_fertility_clinic.employee_demographics;

What I learned:

- "SELECT" specifies the columns I want to retrieve.
- "FROM" identifies the table containing the data.
- "age + 10" calculates a value ten years greater than each employee's recorded age without changing the original data.

2. Retrieving Employees' First Names

SELECT first_name
FROM Eve_and_jay_fertility_clinic.employee_demographics;

What I learned:

I can retrieve just one column by specifying its name after "SELECT". This query returns the first names of all employees in the specified table.

3. Retrieving an Employee's Salary

SELECT salary
FROM Eve_and_jay_fertility_clinic.employee_salary
WHERE first_name = 'Jasmin';

What I learned:

- "SELECT salary" specifies that I want to retrieve salary information.
- "FROM" identifies the table containing the salary information.
- "WHERE first_name = 'Jasmin'" filters the results to records where the first name matches Jasmin.

Note: This query assumes that the "employee_salary" table contains both the "salary" and "first_name" columns.

What Is PEMDAS?

PEMDAS stands for:

- P — Parentheses
- E — Exponents
- M — Multiplication
- D — Division
- A — Addition
- S — Subtraction

It helps explain the order in which mathematical operations are evaluated. SQL follows mathematical operator precedence when evaluating arithmetic expressions.

For example:

SELECT age + 10
FROM Eve_and_jay_fertility_clinic.employee_demographics;

This calculates a new value by adding 10 to each employee's age.

Why I'm Learning SQL

I'm learning SQL to strengthen my technical skills in cybersecurity. I want to understand how structured data is stored, retrieved, and analysed, and eventually apply these skills to practical projects.

This repository will grow as I learn and practise new concepts.


Status: Beginner — actively learning and practising SQL.

Goal: Consistent practice, continuous improvement, and practical projects.