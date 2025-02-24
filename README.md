# **PostgreSQL Full Tutorial Menu List**

## **Introduction to PostgreSQL:**
| Title    | Remark  |
| -------------| -----|
| [What is PostgreSQL?](https://github.com/potatoscript/sql/wiki/What-is-PostgreSQL) | Introduction to PostgreSQL, its features, and advantages. |
| [Installing PostgreSQL](https://github.com/potatoscript/sql/wiki/Installing-PostgreSQL) | A guide to installing PostgreSQL on various operating systems. |
| [PostgreSQL Setup and Configuration](https://github.com/potatoscript/sql/wiki/PostgreSQL-Setup) | Basic setup, configuration, and getting started with PostgreSQL. |

## **Basic SQL Operations:**
| Title    | Remark  |
| -------------| -----|
| [Connecting to PostgreSQL](https://github.com/potatoscript/sql/wiki/Connecting-to-PostgreSQL) | How to connect to a PostgreSQL database using `psql` and other tools. |
| [Database Operations](https://github.com/potatoscript/sql/wiki/Database) | Learn how to create, drop, and manage PostgreSQL databases. |
| [Creating Tables](https://github.com/potatoscript/sql/wiki/CREATE-TABLE) | Creating tables with columns, data types, and constraints. |
| [Inserting Data](https://github.com/potatoscript/sql/wiki/INSERT) | How to insert new records into a PostgreSQL table. |
| [Selecting Data](https://github.com/potatoscript/sql/wiki/SELECT) | Basics of selecting data with the `SELECT` statement, including filtering and sorting. |
| [Updating Data](https://github.com/potatoscript/sql/wiki/UPDATE) | How to update existing records in a table using the `UPDATE` statement. |
| [Deleting Data](https://github.com/potatoscript/sql/wiki/DELETE) | How to delete data from a PostgreSQL table. |
| [TRUNCATE](https://github.com/potatoscript/sql/wiki/TRUNCATE) | Reset auto-increment counter and delete all rows in a table. |

## **Advanced Querying:**
| Title    | Remark  |
| -------------| -----|
| [WHERE Clause](https://github.com/potatoscript/sql/wiki/WHERE) | Using `WHERE` to filter results based on conditions. |
| [AND, OR, NOT Operators](https://github.com/potatoscript/sql/wiki/AND-OR-NOT) | Using logical operators to combine multiple conditions in `WHERE`. |
| [GROUP BY Clause](https://github.com/potatoscript/sql/wiki/GROUP-BY) | Grouping rows to perform aggregate functions like `COUNT`, `AVG`, `SUM`. |
| [HAVING Clause](https://github.com/potatoscript/sql/wiki/HAVING) | Filtering aggregated results using `HAVING`. |
| [ORDER BY Clause](https://github.com/potatoscript/sql/wiki/ORDER-BY) | Sorting query results in ascending or descending order. |
| [DISTINCT](https://github.com/potatoscript/sql/wiki/DISTINCT) | Removing duplicates in the result set using the `DISTINCT` keyword. |
| [JOINS](https://github.com/potatoscript/sql/wiki/JOINS) | Combining data from multiple tables using different types of joins (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`). |
| [Subqueries](https://github.com/potatoscript/sql/wiki/Subqueries) | Using subqueries within `SELECT`, `INSERT`, `UPDATE`, and `DELETE`. |
| [IN, BETWEEN, LIKE](https://github.com/potatoscript/sql/wiki/IN-BETWEEN-LIKE) | Using `IN`, `BETWEEN`, and `LIKE` operators for advanced filtering. |
| [EXPLAIN](https://github.com/potatoscript/sql/wiki/EXPLAIN) | Using `EXPLAIN` to analyze and optimize query performance. |

## **Data Integrity and Constraints:**
| Title    | Remark  |
| -------------| -----|
| [Primary Key](https://github.com/potatoscript/sql/wiki/Primary-Key) | Defining a primary key to uniquely identify each record in a table. |
| [Foreign Key](https://github.com/potatoscript/sql/wiki/Foreign-Key) | Establishing relationships between tables using foreign keys. |
| [Unique Constraints](https://github.com/potatoscript/sql/wiki/Unique-Constraints) | Enforcing uniqueness for specific columns in a table. |
| [Check Constraints](https://github.com/potatoscript/sql/wiki/Check-Constraints) | Using check constraints to ensure data validity. |
| [Not Null Constraint](https://github.com/potatoscript/sql/wiki/Not-Null-Constraint) | Enforcing non-null values for certain columns. |

## **Data Manipulation:**
| Title    | Remark  |
| -------------| -----|
| [UPDATE](https://github.com/potatoscript/sql/wiki/UPDATE) | How to modify records in a table with the `UPDATE` statement. |
| [INSERT with SELECT](https://github.com/potatoscript/sql/wiki/INSERT-with-SELECT) | Inserting data using a `SELECT` statement for bulk insertions. |
| [Upsert (INSERT ON CONFLICT)](https://github.com/potatoscript/sql/wiki/Upsert) | Handling upsert operations using `INSERT ON CONFLICT`. |
| [COPY](https://github.com/potatoscript/sql/wiki/COPY) | Importing and exporting data using the `COPY` command for bulk data management. |
| [Transactional Operations](https://github.com/potatoscript/sql/wiki/Transactions) | Managing transactions with `BEGIN`, `COMMIT`, and `ROLLBACK`. |

## **PostgreSQL Advanced Features:**
| Title    | Remark  |
| -------------| -----|
| [Views](https://github.com/potatoscript/sql/wiki/Views) | Creating and managing views for easier query abstraction. |
| [Materialized Views](https://github.com/potatoscript/sql/wiki/Materialized-Views) | Using materialized views to store complex query results for better performance. |
| [Stored Procedures](https://github.com/potatoscript/sql/wiki/Stored-Procedures) | Creating reusable stored procedures to encapsulate business logic. |
| [Functions](https://github.com/potatoscript/sql/wiki/Functions) | Writing custom functions in PostgreSQL for advanced data manipulation. |
| [Triggers](https://github.com/potatoscript/sql/wiki/Triggers) | Automatically executing SQL statements with triggers before or after changes to the table. |
| [Indexes](https://github.com/potatoscript/sql/wiki/Indexes) | Creating and optimizing indexes to speed up query execution. |
| [Partitioning](https://github.com/potatoscript/sql/wiki/Partitioning) | Splitting large tables into partitions for better performance and scalability. |

## **Advanced PostgreSQL Topics:**
| Title    | Remark  |
| -------------| -----|
| [JSON Support](https://github.com/potatoscript/sql/wiki/JSON-Support) | Working with JSON data types for storing semi-structured data. |
| [Foreign Data Wrappers (FDW)](https://github.com/potatoscript/sql/wiki/Foreign-Data-Wrappers) | Querying external data sources with Foreign Data Wrappers. |
| [Security & Roles](https://github.com/potatoscript/sql/wiki/Security-Roles) | Managing security, roles, and permissions in PostgreSQL. |
| [Backups and Restores](https://github.com/potatoscript/sql/wiki/Backups-and-Restores) | How to backup and restore databases using `pg_dump` and `pg_restore`. |
| [Replication](https://github.com/potatoscript/sql/wiki/Replication) | Setting up replication for high availability and load balancing. |
| [Performance Tuning](https://github.com/potatoscript/sql/wiki/Performance-Tuning) | Optimizing PostgreSQL performance through query optimization, indexing, and server configuration. |

## **PostgreSQL Tools and Extensions:**
| Title    | Remark  |
| -------------| -----|
| [pgAdmin](https://github.com/potatoscript/sql/wiki/pgAdmin) | Using pgAdmin for managing PostgreSQL databases through a graphical interface. |
| [pgBackRest](https://github.com/potatoscript/sql/wiki/pgBackRest) | Using pgBackRest for efficient backup and restore of PostgreSQL databases. |
| [PostGIS](https://github.com/potatoscript/sql/wiki/PostGIS) | Adding geographic object support to PostgreSQL with PostGIS extension. |
| [PostgreSQL Extensions](https://github.com/potatoscript/sql/wiki/PostgreSQL-Extensions) | An overview of PostgreSQL extensions to extend the functionality of PostgreSQL. |
