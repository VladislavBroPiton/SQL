The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates.
The BETWEEN operator is inclusive: begin and end values are included. 
### 1. Use the BETWEEN operator to select all the records where the value of the Price column is between 10 and 20.
```
SELECT * FROM Products
WHERE Price BETWEEN 10 AND 20;
```
### 2. Use the BETWEEN operator to select all the records where the value of the Price column is NOT between 10 and 20.
```
SELECT * FROM Products
WHERE Price NOT BETWEEN 10 AND 20;
```
