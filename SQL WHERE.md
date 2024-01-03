The WHERE clause is used to filter records. It is used to extract only those records that fulfill a specified condition.
```
SELECT * FROM Customers
WHERE Country='Mexico';
```
``Note: The WHERE clause is not only used in SELECT statements, it is also used in UPDATE, DELETE, etc.!``

## The following operators can be used in the WHERE clause:  
#### 1. **``=``**      
```
SELECT * FROM Products  
WHERE Price = 18;  
```
#### 2. **``>``**  
```
SELECT * FROM Products
WHERE Price > 30;
```
#### 3. **``<``**
```
SELECT * FROM Products
WHERE Price < 30;
```
####  4. **``>=``**
```
SELECT * FROM Products
WHERE Price >= 30;
```
#### 5. **``<=``**
```
SELECT * FROM Products
WHERE Price <= 30;
```
#### 6. **``<>``**
```
SELECT * FROM Products
WHERE Price <> 18;
```
#### 7. **``BETWEEN``**
```
SELECT * FROM Products
WHERE Price BETWEEN 50 AND 60;
```
#### 8. **``LIKE``**
```
SELECT * FROM Customers
WHERE City LIKE 's%';
```
#### 9. **``IN``**
```
SELECT * FROM Customers
WHERE City IN ('Paris','London');
```

## Select all records where the City column has the value "Berlin".
```
SELECT * FROM Customers
WHERE City = 'Berlin';
```
## Use the NOT keyword to select all records where City is NOT "Berlin".
```
SELECT * FROM Customers
WHERE NOT City = 'Berlin';
```
## Select all records where the CustomerID column has the value 32.
