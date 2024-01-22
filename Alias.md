SQL aliases are used to give a table, or a column in a table, a temporary name.    
Aliases are often used to make column names more readable.  
An alias only exists for the duration of that query.  
An alias is created with the AS keyword.    
### 1. When displaying the Customers table, make an ALIAS of the PostalCode column, the column should be called Pno instead.
```
SELECT CustomerName,
Address,
PostalCode AS Pno
FROM Customers;
```
### 2. When displaying the Customers table, refer to the table as Consumers instead of Customers.
```
SELECT *
FROM Customers AS Consumers;
```
