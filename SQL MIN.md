The MIN() function returns the smallest value of the selected column.  
The MAX() function returns the largest value of the selected column.
### 1. Use the MIN function to select the record with the smallest value of the Price column.
```
SELECT MIN(Price)
FROM Products;
```
### 2. Use an SQL function to select the record with the highest value of the Price column.
```
SELECT MAX(Price)
FROM Products;
```
### 3. Use the correct function to return the number of records that have the Price value set to 18.
```
SELECT COUNT(*)
FROM Products
WHERE Price = 18;
```
### 4. Use an SQL function to calculate the average price of all products.
```
SELECT AVG(Price)
FROM Products;
```
