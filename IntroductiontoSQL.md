#SQL is a standard language for accessing and manipulating databases.

#What is SQL?
 SQL stands for Structured Query Language
 SQL lets you access and manipulate databases
 SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

#What Can SQL do?

SQL can execute queries against a database
SQL can retrieve data from a database
SQL can insert records in a database
SQL can update records in a database
SQL can delete records from a database
SQL can create new databases
SQL can create new tables in a database
SQL can create stored procedures in a database
SQL can create views in a database
SQL can set permissions on tables, procedures, and views

#Some of The Most Important SQL Commands

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

#The SQL SELECT Statement
The SELECT statement is used to select data from a database.

SELECT CustomerName, City FROM Customers;


Select ALL columns
If you want to return all columns, without specifying every column name, you can use the #SELECT * syntax:

#SQL SELECT DISTINCT Statement
The SELECT DISTINCT statement is used to return only distinct (different) values.

SELECT DISTINCT Country FROM Customers;

#Count Distinct
By using the DISTINCT keyword in a function called COUNT, we can return the number of different countries.
