# Advanced SQL Queries and Aggregations

## Assignment Overview

This assignment focuses on using SQL aggregate functions and clauses to analyze data from the database.

## SQL Concepts Used

* `SUM()` — calculates the total of numeric values.
* `AVG()` — calculates the average of numeric values.
* `MAX()` — finds the highest value.
* `GROUP BY` — groups rows with similar values.
* `ORDER BY` — sorts query results.
* `LIMIT` — restricts the number of rows returned.

## Questions Covered

### Question 1

Calculates the total payment amount for each payment date, sorts the dates from latest to earliest, and displays the top 5 latest payment dates.

### Question 2

Calculates the average credit limit for each customer and displays the customer name and country.

### Question 3

Calculates the total price of products ordered and groups the results by product code and quantity ordered.

### Question 4

Finds the highest payment amount for each check number.

## Database Tables Used

The queries use the following tables:

* `payments`
* `customers`
* `orderdetails`

## Requirements

* MySQL or another SQL-compatible database
* A database containing the required tables
* SQL editor such as MySQL Workbench or Visual Studio Code

## How to Run

1. Open your SQL editor.
2. Connect to your database.
3. Select the database containing the required tables.
4. Copy and run the SQL queries.
5. Check the output for each question.

## Learning Outcome

After completing this assignment, you should understand how to use aggregate functions together with `GROUP BY`, `ORDER BY`, and `LIMIT` to organize and analyze database information.
