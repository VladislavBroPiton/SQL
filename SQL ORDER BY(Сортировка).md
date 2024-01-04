The ORDER BY keyword is used to sort the result-set in ascending or descending order.
### 1. Select all records from the Customers table, sort the result alphabetically by the column City.
```
SELECT * FROM Customers
ORDER BY  City;
```
### 2. Select all records from the Customers table, sort the result reversed alphabetically by the column City.
```
SELECT * FROM Customers
ORDER BY City DESC;
```
### 3. Select all records from the Customers table, sort the result alphabetically, first by the column Country, then, by the column City.
```
SELECT * FROM Customers
ORDER BY Country, City;
```
