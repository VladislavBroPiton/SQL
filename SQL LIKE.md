The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.

There are two wildcards often used in conjunction with the LIKE operator:

 The percent sign % represents zero, one, or multiple characters
 The underscore sign _ represents one, single character

### 1. Select all records where the value of the City column starts with the letter "a".
```
SELECT * FROM Customers
WHERE City LIKE 'a%';
```
### 2. Select all records where the value of the City column ends with the letter "a".
```
SELECT * FROM Customers
WHERE City LIKE '%a';
```
