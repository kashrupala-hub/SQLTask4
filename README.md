This repository shows the usage of aggregate functions, GROUP BY clause, and HAVING clause in SQL 
with practical examples. It also explains the behavior of different variations of the COUNT() function
1) Aggregate Fuctions
   used to perform calculations on multiple rows of a table and return a single summarized value.
   perform various below operations to understand the behaviour of
     SUM(column) → Returns the total sum of numeric values.
     COUNT(*) → Counts all rows in a table (including rows with NULL values).
     COUNT(column) → Counts non-NULL values in a specified column.
     COUNT(DISTINCT column) → Counts the unique, non-NULL values in a column.
     AVG(column) → Returns the average value of a numeric column.
2) GROUP BY Clause
   The GROUP BY clause groups rows that have the same values in specified columns, allowing
   aggregate functions to be applied to each group.i have used  GROUP BY clause with various
   aggregate function
4) HAVING Clause
   The HAVING clause is used to filter groups created by the GROUP BY clause, typically in combination
    with aggregate functions.
