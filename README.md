# SQL_STUDY_NOTES

## 1) What are SQL and its basic syntax?
- SQL or Structured Query Language is a programming language used to manage and manipulate relational databases.

- It is a standard language for managing data stored in relational database management systems (RDBMS) such as MySQL, Oracle, and Microsoft SQL Server.

#### SQL consists of several components, including data definition language (DDL), data manipulation language (DML), data control language (DCL), and transaction control language (TCL).

- DDL is used to create and modify database objects such as tables, indexes, and views.
- DML is used to insert, update, and delete data from tables.
- DCL is used to control access to data in the database,
- while TCL is used to manage transactions.

Here's an example of basic SQL syntax for creating a table:

CREATE TABLE employees ( 
id INT PRIMARY KEY, 
name VARCHAR(50), 
department VARCHAR(50), 
salary INT 
); 

- In this example, we're creating a table named "employees" with four columns: id, name, department, and salary. The "id" column is defined as the primary key, indicating that it uniquely identifies each row in the table
