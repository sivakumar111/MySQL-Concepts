# Structured MySQL Syllabus
1. Introduction to SQL
  •	What is SQL?
  •	Why use SQL?
  •	Advantages & Disadvantages
  •	SQL Database Types:
    o	Relational Databases
    o	Non-relational Databases
2. SQL Commands Classification
  •	DDL (Data Definition Language): CREATE, ALTER, DROP, TRUNCATE
  •	DML (Data Manipulation Language): INSERT, UPDATE, DELETE
  •	DCL (Data Control Language): GRANT, REVOKE
  •	TCL (Transaction Control Language): COMMIT, ROLLBACK, SAVEPOINT
  •	DQL (Data Query Language): SELECT
3. Database Queries
  •	Writing and executing queries
  •	Query optimization basics
4. Data Types in SQL
  •	Numeric Data Types: INT, BIGINT, SMALLINT, TINYINT, DECIMAL, NUMERIC, FLOAT, REAL
  •	Character Data Types: CHAR, VARCHAR, TEXT
  •	Date & Time Data Types: DATE, TIME, DATETIME, TIMESTAMP
  •	Boolean Data Type: BOOLEAN
  •	Binary Data Types: BLOB, BINARY, VARBINARY
  •	Other Data Types: JSON, XML, ENUM, SET
5. Creating Tables and Constraints
  a) Table Creation & Modification
    •	CREATE TABLE
    •	ALTER TABLE
  b) Constraints
    •	PRIMARY KEY
    •	FOREIGN KEY
    •	UNIQUE
    •	NOT NULL
    •	CHECK
    •	DEFAULT
    •	CANDIDATE KEY
    •	ALTERNATE KEY
  c) Table Removal
    •	DROP TABLE
    •	TRUNCATE TABLE
6. SQL Operators
  a) Arithmetic Operators
    •	(+, -, *, /, %)
  b) Comparison Operators
    •	(=, !=, >, <, >=, <=)
  c) Logical Operators
    •	AND, OR, NOT
  d) Other Operators
    •	BETWEEN, IN, NOT IN, LIKE, IS NULL
    •	ALL, ANY, EXISTS, SOME
    •	Wildcards (% and _ with LIKE)
7. Select Queries and Filtering Data
  •	SELECT, FROM, WHERE
  •	DISTINCT
  •	ORDER BY
  •	GROUP BY
  •	HAVING
  •	TOP, PERCENT, WITH TIES
  •	OFFSET FETCH
8. Functions in SQL
  a) Single Row Functions
    •	String Functions: LEN, LOWER, UPPER, SUBSTRING, etc.
    •	Numeric Functions: ROUND, CEIL, FLOOR, etc.
    •	Date Functions: GETDATE(), DATEADD(), DATEDIFF(), etc.
  b) Group Functions (Aggregate)
    •	SUM(), AVG(), COUNT(), MIN(), MAX()
9. Joins in SQL
  •	INNER JOIN
  •	LEFT JOIN
  •	RIGHT JOIN
  •	FULL OUTER JOIN
  •	CROSS JOIN
  •	SELF JOIN
10. Subqueries and Advanced Queries
  •	Subqueries: Single-row, Multi-row, Nested
  •	Common Table Expressions (CTE)
  •	EXISTS, IN, ANY, ALL
11. Views
  •	CREATE VIEW
  •	Types of Views
  •	Advantages & Disadvantages
12. Indexes
  •	Clustered Index
  •	Non-Clustered Index
  •	Unique Index
  •	Why Indexes are Used
13. Stored Procedures
  •	CREATE PROCEDURE
  •	Parameters (IN, OUT)
  •	RETURN Values
  •	Advantages of Stored Procedures
14. Triggers
  •	AFTER Trigger
  •	INSTEAD OF Trigger
  •	DML Triggers (INSERT, UPDATE, DELETE)
15. Cursors
  •	What is a Cursor?
  •	Types of Cursors
  •	DECLARE, OPEN, FETCH, CLOSE, DEALLOCATE
16. Transactions and ACID Properties
  •	START TRANSACTION
  •	COMMIT
  •	ROLLBACK
  •	SAVEPOINT
  •	ACID Properties (Atomicity, Consistency, Isolation, Durability)
17. Temporary Tables & Magic Tables
  •	Temporary Tables (Local, Global)
  •	Magic Tables (Inserted, Deleted in Triggers)
18. Sequences and Identity
  •	SEQUENCE (CREATE, NEXT VALUE FOR)
  •	IDENTITY Columns
19. SQL Injection
  •	What is SQL Injection?
  •	How to Prevent SQL Injection
20. Performance Optimization Techniques
  •	Query Optimization
  •	Index Optimization
  •	Execution Plans
  •	Avoiding Cursors
