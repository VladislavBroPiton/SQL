The INSERT INTO statement is used to insert new records in a table.
```
INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country) 
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
```
CustomerID | CustomerName | ContactName | Address | City | PostalCode | Country
:--|:-------:|:--------------:|:-----:|--------------- | ----------| ----------:
89 | White Clover Markets	| Karl Jablonski | 305 - 14th Ave. S. Suite 3B | Seattle | 98128 | USA
90 | Wilman Kala |	Matti Karttunen |	Keskuskatu 45 |	Helsinki |	21240 |	Finland
91 | Wolski |	Zbyszek |	ul. Filtrowa 68 |	Walla |	01-012 |	Poland
92 | 	Cardinal |	Tom B. Erichsen |	Skagen 21 |	Stavanger |	4006 |	Norway


### 1. Insert a new record in the Customers table.
```
INSERT INTO Customers (CustomerName, Address, City, PostalCode, Country)
VALUES ('Hekkan Burger', 'Gateveien 15', 'Sandnes', '4306','Norway');
```
  
CustomerID | CustomerName | ContactName | Address | City | PostalCode | Country
:--|:-------:|:--------------:|:-----:|--------------- | ----------| ----------:
89 | White Clover Markets	| Karl Jablonski | 305 - 14th Ave. S. Suite 3B | Seattle | 98128 | USA
90 | Wilman Kala |	Matti Karttunen |	Keskuskatu 45 |	Helsinki |	21240 |	Finland
91 | Wolski |	Zbyszek |	ul. Filtrowa 68 |	Walla |	01-012 |	Poland
92 | 	Cardinal |	Tom B. Erichsen |	Skagen 21 |	Stavanger |	4006 |	Norway
93 | Hekkan Burger | NULL | Gateveien 15 | Sandnes | 4306 | Norway 

```
INSERT INTO Customers (CustomerName, City, Country)
VALUES ('Cardinal', 'Stavanger', 'Norway');
```

CustomerID | CustomerName | ContactName | Address | City | PostalCode | Country
:--|:-------:|:--------------:|:-----:|--------------- | ----------| ----------:
89 | White Clover Markets	| Karl Jablonski | 305 - 14th Ave. S. Suite 3B | Seattle | 98128 | USA
90 | Wilman Kala |	Matti Karttunen |	Keskuskatu 45 |	Helsinki |	21240 |	Finland
91 | Wolski |	Zbyszek |	ul. Filtrowa 68 |	Walla |	01-012 |	Poland
92 | 	Cardinal |	NULL |	NULL |	Stavanger |	NULL |	Norway
