# SQL Practice Projects – IBM Data Engineering Foundations

This repository contains SQL practice tasks completed as part of the IBM Data Engineering Foundations course (2022). The exercises were performed on IBM Db2 Cloud, and later some queries were also tested in pgAdmin (PostgreSQL) to validate portability across database systems.

## The work demonstrates my ability to:

Import and explore relational datasets

Define and manage primary keys and foreign keys

Create relationships between tables

Write SQL queries ranging from basic selections to complex joins

Perform filtering, grouping, aggregations, and sorting

Work across multiple SQL database environments (Db2 and PostgreSQL)

## 📂 Repository Structure
IBM_SQL_Practice/
│
├─ README.md              <- Project overview (this file)
├─ data/                  <- Source datasets in Excel format
│   ├─ employees.xlsx
│   ├─ departments.xlsx
│   └─ orders.xlsx
├─ queries/               <- SQL query files (.sql)
│   ├─ task3B.sql
│   ├─ task4A.sql
│   └─ ...
├─ screenshots/           <- Screenshots of queries and outputs
│   ├─ Task3B.JPG
│   ├─ Task4A.JPG
│   └─ ...

## 🗂️ Example Tasks
Task	Dataset(s)	Objective	Skills Demonstrated
3B	Employees.xlsx	Calculate average salary per department	GROUP BY, AVG, JOIN
4A	Orders.xlsx, Products.xlsx	Find total sales by product category	SUM, JOIN, ORDER BY
…	Multiple linked tables	Query data across related tables using foreign keys	Schema design, constraints, JOINs

(More examples in the queries/ and screenshots/ folders)

## 🛠️ Skills Demonstrated

Database design: Creating schemas, setting primary and foreign keys, enforcing relationships

## SQL querying:

Filtering with WHERE

Aggregation with GROUP BY, HAVING, COUNT, SUM, AVG

Sorting with ORDER BY

Complex joins across multiple tables

Multi-environment SQL practice: Running queries in both IBM Db2 Cloud and pgAdmin (PostgreSQL)

## 🚀 How to Use

Open the .sql files inside the queries/ folder to view individual queries.

Datasets are available in the data/ folder for reference.

Screenshots in screenshots/ illustrate query results as run on IBM Db2 Cloud.

Most queries can also be run on PostgreSQL (pgAdmin) with minor syntax adjustments.

## 📌 Notes

These exercises were originally part of the IBM course Data Engineering Foundations (2022).

The course structure may have changed since then, but this repository reflects my completed work and SQL skills.

While the datasets are simplified, the tasks simulate real-world problems such as employee management, order tracking, and departmental reporting.
