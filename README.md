# Data-Analysis-Using-SQL
Excel is a great application for a beginner to learn data analysis, but it has it’s own
limitations. It can't handle very large datasets, and data cleaning, transformation and
analysis on large datasets can easily turn out to be a painful exercise.
Structured Query Language (SQL) overcomes these limitations of Excel. SQL can be
used to join several tables in a relational database to get a very large dataset.
Performing data-transformations and analysis using SQL is also very easy and fast.
In this SQL project, we will create a database called ‘classicmodels’ to store
business data related to classic cars such as information about customers, products,
sales orders, sales order line items, and more. This database example is taken from
https://www.mysqltutorial.org/getting-started-with-mysql/mysql-sample-database/
The MySQL sample database schema consists of the following tables:

customers: stores customer’s data.
products: stores a list of scale model cars.
productlines: stores a list of product lines.
orders: stores sales orders placed by customers.
orderdetails: stores sales order line items for every sales order.
payments: stores payments made by customers based on their accounts.
employees: stores employee information and the organization structure such
as who reports to whom.
offices: stores sales office data.

When we began our SQL journey with the online_retail_dataset, we essentially
focussed on how to split the big excel sheet into smaller tables and what will be the
best choices for these small tables. This is like the first step in database design. We
also practised many Data Definition Language (DDL) queries for creating, dropping,
and altering tables. However, now we are going to focus on the data analysis part
where we assume that someone has already given us the normalized table structure
and the table contents. We will directly go to questions on analyse data in sql tables
using queries.
1. Creating the necessary tables and inserting data: Download the .sql file from
here: https://www.mysqltutorial.org/wp-
content/uploads/2023/10/mysqlsampledatabase.zip and use it for creating
tables and populating the tables with data
2. Print the number of rows present in each of the following tables:
   a. productlines;
   b. products;
   c. offices;
   d. employees;
   e. customers;
   f. payments;
   g. orders;
   h. orderdetails;
4. What is the total number of orders placed by each customer?
5. What is the total amount spent by each customer?
6. List the top 5 highest spending customers.
7. How many customers each sales employee deals with?
8. List the top 5 employees with the highest total sales volumes.
9. Which month has the most orders in every year?
10. Which product is the most ordered one?
11. Which office location has the highest sales?
