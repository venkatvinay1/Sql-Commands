# Sql-Commands

## SQL Basics

SELECT * FROM table_name;

SELECT CustomerName, City FROM Customers;

SELECT DISTINCT Country FROM Customers;

SELECT COUNT(DISTINCT Country) FROM Customers;

SELECT * FROM Customers
WHERE Country='Mexico';

SELECT * FROM Products
WHERE Price < 30;

SELECT * FROM Products
WHERE Price > 30;

Different sets of operators can be used with the where clause.

SELECT * FROM Customers
WHERE Country='Germany' AND City='Berlin';

SELECT * FROM Customers
WHERE City='Berlin' OR City='München';

SELECT * FROM Customers
WHERE NOT Country='Germany';

SELECT * FROM Customers
WHERE Country='Germany' AND (City='Berlin' OR City='München');


