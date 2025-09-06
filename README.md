# SQL-Problem-Solving-Series

This repository contains a series of SQL practice problems and solutions designed to help learners strengthen their SQL skills. It covers a wide range of topics from basic queries to advanced SQL concepts.

## Topics Covered

* Basic SELECT queries
* Filtering using WHERE conditions
* Aggregate functions: COUNT, SUM, AVG, MIN, MAX
* String functions: CONCAT, UPPER, LOWER, SUBSTRING
* Numeric functions: ROUND, CEIL, FLOOR, ABS
* Date and time functions: NOW, CURDATE, DATEDIFF
* Conditional functions: CASE, COALESCE, NULLIF
* Sorting with ORDER BY and limiting rows using LIMIT/OFFSET
* Grouping data using GROUP BY and HAVING
* Joins: INNER JOIN, LEFT JOIN, RIGHT JOIN, SELF JOIN
* Ranking and window functions: ROW\_NUMBER(), RANK(), DENSE\_RANK()

## Purpose

The goal of this repository is to provide a structured way to **practice and master SQL** through real-life inspired problems. Each problem includes:

1. A description of the problem
2. Sample data or tables
3. SQL query solution with explanations and comments

This is ideal for students, developers, and anyone preparing for **SQL interviews or competitive coding challenges**.

---

## 🔹 Easy (Basic Queries & Simple Joins)

1. Count total employees (`COUNT(*)`)
2. Find highest salary (`MAX()`)
3. Find lowest salary (`MIN()`)
4. Find average salary (`AVG()`)
5. List employees hired after a specific date (`WHERE` + `>=`)
6. Display employee names in uppercase (`UPPER()`)
7. Display employee names in lowercase (`LOWER()`)
8. List first 5 employees (`LIMIT`)
9. Find employees in a specific department (`WHERE Department = 'IT'`)
10. Show distinct departments (`DISTINCT`)
11. Find employees with NULL manager (`IS NULL`)
12. Find employees whose salary is above 50,000 (`WHERE Salary > 50000`)
13. Employees whose name starts with a specific letter (`LIKE 'A%'`)
14. Employees whose name contains a substring (`LIKE '%an%'`)
15. Simple join: Show employees with their department names (`INNER JOIN Departments`)

---

## 🔹 Medium (Aggregates, Grouping, Joins, Subqueries)

1. Count employees per department (`GROUP BY`)
2. Total salary per department (`SUM(Salary) GROUP BY Department`)
3. Average salary per department (`AVG(Salary) GROUP BY Department`)
4. Find 2nd highest salary (`MAX()` + subquery)
5. Find 3rd highest salary (`MAX()` + nested subqueries)
6. Find employees with salary greater than department average (`JOIN` or subquery)
7. Top 3 highest salaries (`ORDER BY Salary DESC LIMIT 3`)
8. Count employees joined after 2020 per department (`GROUP BY + WHERE`)
9. Employees who belong to multiple departments (`JOIN` or `GROUP_CONCAT` equivalent)
10. Employees not in a specific department (`WHERE NOT IN` or `LEFT JOIN IS NULL`)
11. Show employee with their manager name (`SELF JOIN`)
12. Show employees and their department along with department head (`JOIN`)
13. Employees whose salary is above average using a subquery
14. Department-wise highest and lowest salary (`GROUP BY + MAX/MIN`)
15. Rank employees by salary using window function (`ROW_NUMBER()` / `RANK()` if supported)

---

✅ These **30 problems** are a good mix of:

* **Easy** → simple filters, aggregates, string functions, simple joins.
* **Medium** → grouping, subqueries, multiple joins, ranking, and commonly asked SQL interview questions.


