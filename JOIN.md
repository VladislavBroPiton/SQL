A JOIN clause is used to combine rows from two or more tables, based on a related column between them.
### 1. Insert the missing parts in the JOIN clause to join the two tables Orders and Customers, using the CustomerID field in both tables as the relationship between the two tables.
```
SELECT *
FROM Orders
LEFT JOIN Customers
ON Orders.CustomerID=Customers.CustomerID;
```
### 2. Choose the correct JOIN clause to select all records from the two tables where there is a match in both tables.
```
SELECT *
FROM Orders
INNER JOIN Customers
ON Orders.CustomerID=Customers.CustomerID;
```
### 3. Choose the correct JOIN clause to select all the records from the Customers table plus all the matches in the Orders table.
```
SELECT *
FROM Orders
RIGHT JOIN Customers
ON Orders.CustomerID=Customers.CustomerID;
```
