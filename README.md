# Pizza-SQL_project-
This project analyzes pizza sales data using SQL to uncover key business insights. The dataset includes order transactions, pizza details, and customer preferences.

**Key Insights Generated**

1.Total revenue, average order value, and total pizzas sold

2.Best-selling pizzas by quantity and revenue

3.Sales trends by day, week, and month

4.Most popular pizza sizes and categories

5.Peak order hours to optimize staffing

**Tech Stack**

1.SQL (PostgreSQL/MySQL/SQLite)

2.Data Source: CSV files with tables: orders, order_details, pizzas, and pizza_types

**Use Cases**

1.Ideal for practice in:

2.Data cleaning and joins

3.Aggregations and subqueries

4.Sales trend and performance reporting

**These code for upload a table into MySQL**

create database Pizzahut;
create table orders (
order_id int not null primary key,
order_date date not null,
order_time time not null
);

create table order_details (
order_details_id int not null primary key,
order_id int not null,
pizza_id text not null,
quantity int not null
);
