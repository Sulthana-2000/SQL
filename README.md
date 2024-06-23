# SQL

# What is SQL?
SQL (Structured Query Language) is a standard programming language specifically designed for managing and manipulating databases.
It is widely used for querying, inserting, updating, and deleting data in relational database management systems (RDBMS).

# Key Components of SQL

1) Data Definition Language (DDL)
 CREATE: Creates new tables, databases, indexes, or views.
 ALTER: Modifies existing database structures, such as tables.
 DROP: Deletes tables, databases, or views.
 TRUNCATE: Removes all records from a table, but not the table itself.

2) Data Manipulation Language (DML)
 SELECT: Retrieves data from one or more tables.
 INSERT: Adds new records to a table.
 UPDATE: Modifies existing records in a table.
 DELETE: Removes records from a table.

3) Data Control Language (DCL)
 GRANT: Gives user access privileges to the database.
 REVOKE: Withdraws user access privileges given with the GRANT command.

4)Transaction Control Language (TCL)
 COMMIT: Saves all changes made during the current transaction.
 ROLLBACK: Reverts all changes made during the current transaction.
 SAVEPOINT: Sets a savepoint within a transaction to which you can later roll back.

SQL is a powerful and versatile language essential for database management. 
Mastering SQL allows you to effectively interact with relational databases, making it a crucial skill for developers, data analysts, and database administrators.

# WHERE clause in SQL
The 'WHERE' clause in SQL is used to filter records in a SQL query, ensuring that only the rows that meet specified criteria are returned.
It is commonly used with 'SELECT', 'UPDATE', 'DELETE', and other SQL statements.

# Components of the WHERE Clause

Condition: A condition is an expression that returns true or false. Rows for which the condition evaluates to true are included in the result set.

# Comparison Operators:-

> '=' : Equal to
> '<>' or '!=' : Not equal to
> '>' : Greater than
> '<' : Less than
> '>=' : Greater than or equal to
> '<=' : Less than or equal to
> 'BETWEEN' ... 'AND' ... : Within a range
> 'LIKE' : Pattern matching
> 'IN' : Specifies multiple possible values for a column
> 'IS NULL' : Checks for null values

# Logical Operators:-
> 'AND' : Combines two conditions and returns true only if both conditions are true
> 'OR' : Combines two conditions and returns true if either condition is true
> 'NOT' : Reverses the result of a condition

The 'WHERE' clause is a powerful tool in SQL that allows for precise control over which records are retrieved, updated, or deleted in a database.
Understanding how to use it effectively is fundamental to performing efficient and accurate database operations.









 
