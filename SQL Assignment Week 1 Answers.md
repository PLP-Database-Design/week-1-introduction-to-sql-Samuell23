# SQL Assignment Week 1 Answers

## 1. State and Explain the Components of a DBMS (Database Management System)

A Database Management System (DBMS) consists of the following components:

- **Hardware**: The physical devices used for storing and accessing the database (e.g., servers, hard drives).
- **Software**: The actual DBMS software (e.g., MySQL, PostgreSQL) that allows users to interact with the database.
- **Data**: The raw information stored in the database, organized into tables.
- **Users**:
  - **End Users**: Individuals who interact with the database through applications.
  - **Database Administrators (DBAs)**: Professionals responsible for managing and maintaining the database.
- **Procedures**: The guidelines and rules for database management, such as backup and recovery processes.

---

## 2. What is a Relational Database? Give 4 Examples.

A relational database is a type of database that stores data in structured tables with rows and columns. Relationships between tables are defined using keys.

**Examples:**
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

---

## 3. State and Explain Three Classifications of SQL
SQL is classified into the following categories:

1. **Data Definition Language (DDL)**: 
   Used to define and modify database structures. Examples: `CREATE`, `ALTER`, `DROP`.

2. **Data Manipulation Language (DML)**: 
   Used to retrieve and manipulate data within the database. Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

3. **Data Control Language (DCL)**: 
   Used to manage access to the database. Examples: `GRANT`, `REVOKE`.

---

## 4. What is the Difference Between a Primary Key and a Foreign Key?

- **Primary Key**:
  - Uniquely identifies each record in a table.
  - Cannot have duplicate or NULL values.
  - Example: `id` column in a "Users" table.

- **Foreign Key**:
  - A column that establishes a relationship between two tables.
  - Refers to the primary key in another table.
  - Example: `user_id` in a "Orders" table referencing `id` in a "Users" table.

---

## 5. What is an Entity-Relationship Diagram?

An **Entity-Relationship Diagram (ERD)** is a visual representation of a database's structure. It shows entities (tables), their attributes (columns), and the relationships (connections) between them.

**Example Elements in an ERD**:
- Entities: Represented by rectangles.
- Relationships: Represented by diamonds or lines.
- Attributes: Represented by ovals or fields within entities.

---

## 6. What are the Advantages of Relational Databases?

1. **Data Integrity**: Maintains accuracy and consistency across tables using constraints.

2. **Scalability**: Supports large amounts of data with indexing and partitioning.

3. **Ease of Querying**: Provides powerful querying capabilities using SQL.
4. **Relationships**: Efficiently manages relationships between data in different tables.

---

## 7. State Four Types of Data Types Used to Store Data in Tables

1. **Integer**: Stores whole numbers (e.g., `INT`, `BIGINT`).
2. **Character**: Stores strings (e.g., `CHAR`, `VARCHAR`).
3. **Date and Time**: Stores date and time values (e.g., `DATE`, `DATETIME`).
4. **Boolean**: Stores logical values (`TRUE` or `FALSE`).

---

## 8. What is the Purpose of a Database Management System (DBMS)?

The primary purpose of a DBMS is to provide an efficient, secure, and convenient way to store, retrieve, and manage data. It ensures data consistency, supports multi-user access, and enforces rules for data integrity.



