# SQL Commands 

## SELECT

```sql
SELECT column_name FROM table_name;
Example:
SELECT First_Name FROM Students;
```

`SELECT` statements are used to fetch data from a database. Every query will begin with SELECT.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## SELECT DISTINCT

```sql
SELECT DISTINCT column_name FROM table_name;
Example:
SELECT DISTINCT Country FROM Customers;
```

`SELECT DISTINCT` specifies that the statement is going to be a query that returns unique values in the specified column(s).

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## WHERE

```sql
SELECT column_name(s)
FROM table_name
WHERE column_name operator value;
Example:
SELECT * FROM Customers
WHERE CustomerID=1;
```

`WHERE` is a clause that indicates you want to filter the result set to include only rows where the following *condition* is true.
Operator Used 
```sql
=	Equal	
>	Greater than	
<	Less than	
>=	Greater than or equal	
<=	Less than or equal	
<>	Not equal. Note: In some versions of SQL this operator may be written as !=	
BETWEEN : Between a certain range	
LIKE:	Search for a pattern	
IN	: To specify multiple possible values for a column
```
<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

- The WHERE clause can be combined with AND, OR, and NOT operator

## ALTER TABLE

```sql
ALTER TABLE table_name ADD column datatype;
Example:
ALTER TABLE Customers
ADD Email varchar(255);
```

`ALTER TABLE` lets you  add, delete, or modify columns in an existing table.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## AND

```sql
SELECT column_name(s)
FROM table_name
WHERE column_1 = value_1
AND column_2 = value_2;
Example:
SELECT * FROM Customers
WHERE Country='Germany' AND City='Berlin';
```

`AND` is an operator that combines two conditions. Its  displays a record if all the conditions separated by AND are TRUE.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## OR

```sql
SELECT column_name
FROM table_name
WHERE column_name = value_1
OR column_name = value_2;
Example:
SELECT * FROM Customers
WHERE City='Berlin' OR City='München';
```

`OR` is an operator that  displays a record if any of the conditions separated by OR is TRUE.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## ORDER BY

```sql
SELECT column_name
FROM table_name
ORDER BY column_name ASC|DESC;
Example:
SELECT * FROM Customers
ORDER BY Country DESC;
```

`ORDER BY` is a clause that indicates you want to sort the result set by a particular column either alphabetically or numerically.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## INSERT

```sql
INSERT INTO table_name (column_1, column_2, column_3) VALUES (value_1, 'value_2', value_3);
Example:
INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
```

`INSERT` statements are used to add a new row to a table.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>


