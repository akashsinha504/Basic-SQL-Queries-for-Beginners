# Basic SQL Queries for Beginners

This repository contains a set of basic SQL queries designed for anyone starting their journey into SQL and data handling. It includes:

- Creating tables
- Inserting data
- Filtering with `WHERE`
- Sorting with `ORDER BY`
- Deleting data
- Altering data
- Updating and Modifying data
- Practice project using a sample `employee` table

## Table Example

Example table: `TABLE_01 (EMPLOYEE_NAME, AGE, DEPARTMENT, EXPERIENCE, SALARY)`

Sample query:
```sql
SELECT EMPLOYEE_NAME, SALARY 
FROM TABLE_01 
WHERE DEPARTMENT = 'BANKING' 
ORDER BY SALARY DESC;
