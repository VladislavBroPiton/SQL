The RIGHT JOIN keyword returns all records from the right table (table2), and the matching records from the left table (table1). The result is 0 records from the left side, if there is no match.
### 1. List the number of customers in each country.
```
SELECT COUNT (CustomerID),
Country
FROM Customers
GROUP BY Country;
```
