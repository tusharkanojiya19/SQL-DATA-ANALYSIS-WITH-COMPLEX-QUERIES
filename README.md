# DATA-ANALYSIS-WITH-COMPLEX-QUERIES

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: TUSHAR KANOJIYA

*INTERN ID*: CTIS7284

*DOMAIN*: SQL

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: TASK-2: DATA ANALYSIS WITH COMPLEX QUERIES

This task focuses on performing advanced data analysis using complex SQL queries. It demonstrates the use of important SQL concepts such as window functions, subqueries, and Common Table Expressions (CTEs) to extract meaningful insights from structured data. The main objective of this task is to enhance the ability to analyze data efficiently and perform operations beyond basic queries.

In this task, a sample database named “company” is created, and an “employees” table is defined with attributes such as employee ID, employee name, department, salary, and joining date. The table is then populated with sample data to simulate a real-world scenario. This dataset is used to perform various analytical operations using advanced SQL techniques.

One of the key concepts used in this task is the Common Table Expression (CTE). A CTE named “dept_avg” is created to calculate the average salary for each department. This helps in simplifying complex queries and improving readability. By using the GROUP BY clause, the average salary of employees within each department is computed, allowing better understanding of departmental salary distribution.

Subqueries are also utilized in this task to perform nested operations. For example, a query is written to retrieve employees whose salary is greater than the average salary of all employees. This type of query helps in identifying high-performing or higher-paid employees within the organization. Subqueries make it possible to perform calculations within a query and use the result as a condition for filtering data.

Another important feature demonstrated in this task is the use of window functions. The RANK() function is applied with PARTITION BY the department to assign rankings to employees based on their salary in descending order. This allows comparison of employees within the same department and helps in identifying top earners in each group. Window functions are powerful tools for performing calculations across a set of rows related to the current row.

Additionally, the SUM() window function is used with ORDER BY joining date to calculate a running total of salaries. This generates a cumulative sum of salaries as employees are ordered by their joining date. The output clearly shows how the total salary increases with each record, which is useful for tracking growth or trends over time.

The result of these queries is displayed in a structured format, showing employee names, salaries, and running salary totals. This output demonstrates how advanced SQL queries can be used to transform raw data into meaningful information. Proper formatting and logical structuring of queries ensure clarity and easy interpretation of results.

The deliverable of this task includes a set of complex SQL queries along with their outputs. Each query is designed to highlight a specific concept such as CTEs, subqueries, or window functions. This task strengthens the understanding of advanced SQL operations and improves analytical thinking skills.

Overall, this task provides hands-on experience in data analysis using SQL and prepares for handling real-world datasets efficiently.

