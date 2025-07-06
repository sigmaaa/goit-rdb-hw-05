# goit-rdb-hw-05

## Homework Description

Write an SQL query that displays the order_details table and the customer_id field from the orders table, respectively, for each record in the order_details table.
This must be done using a subquery in the SELECT statement.

Write an SQL query that displays the order_details table. Filter the results so that the corresponding record from the orders table meets the condition shipper_id = 3.
This must be done using a subquery in the WHERE clause.

Write an SQL query with a subquery in the FROM clause, which selects rows with the condition quantity > 10 from the order_details table. For the obtained data, calculate the average value of the quantity field — the grouping should be done by order_id.

Solve task 3 using the WITH clause to create a temporary table named temp. If your MySQL version is earlier than 8.0, create this query in the same way as shown in the lecture notes.

Create a function with two parameters that divides the first parameter by the second. Both parameters and the return value should be of type FLOAT.
Use the DROP FUNCTION IF EXISTS construct. Apply the function to the quantity attribute of the order_details table. The second parameter can be any arbitrary number of your choice.
