# databricks-training
## Day 1: SQL Fundamentals
### Basic SELECT Queries
Started with simple stuff — selecting all columns, picking specific fields like name and salary, and filtering rows using WHERE conditions.
### Pattern Matching with LIKE
Practiced finding names that start with a certain letter, end with one, or contain a character somewhere in the middle using `%` and `_` wildcards.
### Date Filtering
Wrote queries to filter employees based on their hire date — within a specific year, between two dates, or hired within the last 2 years using relative date functions.
### Aggregate Functions
Used `SUM`, `AVG`, `MIN`, `MAX`, and `COUNT` to calculate things like total salary, average age, and number of employees per department.
### GROUP BY and HAVING
Grouped data by department and applied filters on grouped results — for example, finding departments with more than 2 employees or an average salary above a certain amount.
### ORDER BY and LIMIT
Sorted results by salary, age, and hire date, and used `LIMIT` to pull only the top result (like the highest-paying department).
### JOINs
Practiced `INNER JOIN` and `LEFT JOIN` across the Employee, Department, and Project tables — things like finding which employees belong to which department, or identifying employees not assigned to any project.
### Subqueries
Wrote correlated and non-correlated subqueries — finding employees who earn more than the average salary of their own department, getting the second or third highest salary, and more.
### Combined Queries
Towards the end, mixed multiple concepts together — joins with aggregates, subqueries inside HAVING, filtering by date with grouping, etc.
## Tables Used

- **Employee** – emp_id, name, age, salary, department_id, hire_date  
- **Department** – department_id, name  
- **Project** – project_id, name, department_id