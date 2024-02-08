The IN operator allows you to specify multiple values in a WHERE clause.
The IN operator is a shorthand for multiple OR conditions.
### 1. Use the IN operator to select all the records where Country is either "Norway" or "France".
```
SELECT * FROM Customers
WHERE Country IN ('Norway', 'France');
```
### 2.  Use the IN operator to select all the records where Country is NOT "Norway" and NOT "France".
```
SELECT * FROM Customers
WHERE Country NOT IN ('Norway', 'France');
``` 
