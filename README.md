# HarryShop E-Commerce Database Project | MySQL

## Overview

HarryShop is a fictional e-commerce merchandise store for programmers, selling coding-themed products such as hoodies, mugs, notebooks, stickers, and accessories.

This project demonstrates end-to-end database development using MySQL, including database design, schema creation, table relationships, data population, and business-oriented SQL analysis.

---

## Project Objectives

* Design a relational database for an e-commerce platform.
* Implement primary and foreign key relationships.
* Store and manage customer, product, order, and payment information.
* Perform business analytics using SQL queries.
* Generate insights from transactional sales data.

---

## Database Design

The database consists of five interconnected tables:

### Customers

Stores customer information including:

* Customer ID
* Name
* Email
* City
* Signup Date

### Products

Stores product catalog details:

* Product ID
* Product Name
* Category
* Price
* Inventory Stock

### Orders

Tracks customer purchases:

* Order ID
* Customer ID
* Order Date
* Order Status

### Order Items

Stores product-level order details:

* Order Item ID
* Order ID
* Product ID
* Quantity

### Payments

Stores payment transaction information:

* Payment ID
* Order ID
* Payment Method
* Amount
* Payment Date

---

## Key SQL Concepts Demonstrated

### Database Design

* Relational Database Modeling
* Entity Relationship Structure
* Normalized Table Design

### SQL Fundamentals

* CREATE DATABASE
* CREATE TABLE
* INSERT INTO
* PRIMARY KEY
* FOREIGN KEY
* AUTO_INCREMENT

### Data Analysis Techniques

* Aggregations using SUM() and COUNT()
* INNER JOIN operations
* GROUP BY
* ORDER BY
* Business KPI calculations

---

## Business Analysis Performed

### Total Revenue Analysis

Calculated total revenue generated from all successful payments.

### Revenue by Product

Identified products contributing the highest revenue.

### Top Customers Analysis

Ranked customers based on total spending.

### Best Selling Products

Determined products with the highest quantity sold.

### Order Status Analysis

Measured cancelled orders to evaluate order fulfillment performance.

---

## Skills Demonstrated

* MySQL
* Relational Database Design
* Data Modeling
* Database Normalization
* Primary & Foreign Keys
* SQL Joins
* Aggregate Functions
* Business Intelligence Queries
* Sales Data Analysis
* E-Commerce Data Management

---

## Project Structure

```text
HarryShop-Database-Project/
│
├── database_schema.sql
├── sample_data.sql
├── business_analysis_queries.sql
├── README.md
```

---

## Future Improvements

* Add Views for reporting
* Create Stored Procedures
* Implement Triggers
* Build Sales Dashboard in Power BI
* Add Inventory Management Reports
* Develop Customer Segmentation Analysis

---

## Author

Shahnawaj Siddique

Aspiring Data Analyst skilled in SQL, Power BI, Excel, Python, Tableau, and AI-Powered Analytics.
