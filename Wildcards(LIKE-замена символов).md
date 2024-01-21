A wildcard character is used to substitute one or more characters in a string.  
Wildcard characters are used with the LIKE operator. The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.  
### 1. Select all records where the second letter of the City is an "a".
```
SELECT * FROM Customers
WHERE City LIKE '_a%';
```
### 2. Select all records where the first letter of the City is an "a" or a "c" or an "s".
```
SELECT * FROM Customers
WHERE City LIKE '[acs]%';
```
### 3. Select all records where the first letter of the City starts with anything from an "a" to an "f".
```
SELECT * FROM Customers
WHERE City LIKE '[a-f]%';
```
### 4. Select all records where the first letter of the City is NOT an "a" or a "c" or an "f".
```
SELECT * FROM Customers
WHERE City LIKE '[!acf]%';
```
