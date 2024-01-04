### 1. Update the City column of all records in the Customers table.
```
UPDATE Customers
SET City = 'Olso';
```
### 2. Set the value of the City columns to 'Oslo', but only the ones where the Country column has the value "Norway".
```
UPDATE Customers
SET City = 'Oslo'
WHERE Country = 'Norway';
```
### 3. Update the City value and the Country value.

