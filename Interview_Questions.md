# **Cracking the SQL Interview**
SQL - Structured Query Language is a domain-specific language used in programming and designed for managing data held in a relational database management system (RDBMS), or for stream processing in a relational data stream management system (RDSMS).

**1. What Can SQL do?

-   SQL can execute queries against a database
-   SQL can retrieve data from a database
-   SQL can insert records in a database
-   SQL can update records in a database
-   SQL can delete records from a database
-   SQL can create new databases
-   SQL can create new tables in a database
-   SQL can create stored procedures in a database
-   SQL can create views in a database
-   SQL can set permissions on tables, procedures, and views

**2. What does SQL stand for?**

SQL stands for Structured Query Language.
SQL lets you access and manipulate databases.
SQL is an ANSI (American National Standards Institute) standard.

**Some of The Most Important SQL Commands**

```sql
SELECT - extracts data from a database
UPDATE - updates data in a database
DELETE - deletes data from a database
INSERT INTO - inserts new data into a database
CREATE DATABASE - creates a new database
ALTER DATABASE - modifies a database
CREATE TABLE - creates a new table
ALTER TABLE - modifies a table
DROP TABLE - deletes a table
CREATE INDEX - creates an index (search key)
DROP INDEX - deletes an index
```
**3. What is MySQL?**

MySQL is the most popular Open Source SQL database management system developed, distributed, and supported by Oracle Corporation.

**Another common SQL interview question regarding MySQL may come in a different form**

“**What is the difference between SQL and MySQL?**” or **Difference between SQL and MySQL:**

SQL is a structured query language that is used for manipulating and accessing the relational database, on the other hand, MySQL itself is a relational database that uses SQL as the standard database language.

**3. What is Database?**
A database is a structured collection of data that is organized for efficient storage, retrieval, and manipulation. It typically consists of tables or collections of related data, which are further divided into records or documents with fields or attributes that describe the data.

**16. Which SQL statement is used to return only different values?**

The SELECT DISTINCT statement is used to return only distinct (different) values.

Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

**SELECT DISTINCT Syntax**  

```sql
SELECT DISTINCT column1, column2, ...
FROM table_name;
```

**81. What are valid constraints in MySQL?**

SQL constraints are used to specify rules for the data in a table.

Constraints are used to limit the type of data that can go into a table. This ensures the accuracy and reliability of the data in the table. If there is any violation between the constraint and the data action, the action is aborted.

Constraints can be column level or table level. Column level constraints apply to a column, and table level constraints apply to the whole table.

The following constraints are commonly used in SQL:

- NOT NULL - Ensures that a column cannot have a NULL value

- UNIQUE - Ensures that all values in a column are different

- PRIMARY KEY - A combination of a NOT NULL and UNIQUE . Uniquely identifies each row in a table

- FOREIGN KEY - Uniquely identifies a row/record in another table

- CHECK - Ensures that all values in a column satisfies a specific condition

- DEFAULT - Sets a default value for a column when no value is specified

- INDEX - Used to create and retrieve data from the database very quickly

  
