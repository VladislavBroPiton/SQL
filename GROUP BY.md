The GROUP BY statement groups rows that have the same values into summary rows, like "find the number of customers in each country".
The GROUP BY statement is often used with aggregate functions (COUNT(), MAX(), MIN(), SUM(), AVG()) to group the result-set by one or more columns.  
### 1. List the number of customers in each country.  
```
SELECT COUNT (CustomerID),
Country
FROM Customers
GROUP BY Country;
```
### 2. List the number of customers in each country, ordered by the country with the most customers first.
```
SELECT COUNT (CustomerID),
Country
FROM Customers
GROUP BY Country
ORDER BY COUNT(CustomerID) DESC;
```
