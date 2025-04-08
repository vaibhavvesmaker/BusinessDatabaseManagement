# MySQL Data Management and Analysis Superstore Dataset

This repository contains SQL scripts for importing, cleaning, and analyzing data from the Superstore dataset in MySQL. The dataset consists of information about orders, customers, products, and transactions.
 
## Contents 

1. [Import dataset to MySQL database](#import-dataset-to-mysql-database)
2. [Data Cleaning](#data-cleaning)
3. [Creation of normalized tables and Indexes in MySQL](#creation-of-normalized-tables-and-indexes-in-mysql)
4. [SQL Questions](#sql-questions)

## Import dataset to MySQL database

- The script creates a MySQL database named "Final_project".
- It creates a table named "Superstore" with columns for various attributes such as order ID, order date, ship date, customer details, product details, sales, quantity, discount, and profit.
- The dataset is then imported into the "Superstore" table.

## Data Cleaning

- Identifies and handles missing or inconsistent data in the dataset.
- Removes records for the company "Sample A Company".
- Updates the format of the "Corey-Lock" name into separate first and last names.
- Adds leading zeros to postal codes that are missing digits.
- Updates product IDs associated with multiple product names to assign unique product IDs for each product name.

## Creation of normalized tables and Indexes in MySQL

- Creates normalized tables for regions, customers, transactions, categories, products, and order items.
- Inserts data into these tables from the "Superstore" table.
- Defines foreign key constraints to maintain referential integrity.
- Creates indexes to improve query performance.

## SQL Questions

- Answers various SQL questions related to the dataset, such as identifying top-selling products, calculating total profit by category, and analyzing customer behavior.
- Queries include filtering, aggregation, sorting, and joining operations to extract meaningful insights from the data.

## Contributors

- Vaibhav Vesmaker (vaibhav.vesmaker@rutgers.edu)

For any inquiries, please contact Vaibhav Vesmaker.
