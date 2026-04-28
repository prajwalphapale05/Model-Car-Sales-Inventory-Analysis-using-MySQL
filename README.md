# Model-Car-Sales-Inventory-Analysis-using-MySQL
Analyzed a 9-table MySQL database to extract insights on sales, inventory, and customer behavior using SQL queries and views. Identified warehouse optimization, improved inventory turnover, evaluated product performance, and provided recommendations to boost revenue, retention, and regional growth.

Project Overview
Mint Classics is a classic model car retailer considering the closure of one of its storage facilities while maintaining high levels of customer service. The analysis within this project explores sales trends, customer retention, and inventory management, providing actionable recommendations for improving efficiency and profitability.

Key Objectives:
Analyse product sales, inventory turnover, and warehouse utilization to determine which facility should close.
Identify underperforming products that may be discontinued.
Analyze customer purchasing behavior and recommend retention strategies.
Evaluate sales representatives' performance across regions.
Dataset Overview
The data used in this project consists of nine tables from the Mint Classics database, which models the company’s operations. The tables include:

Products: Contains product details, availability, and pricing.
Warehouses: Stores information about Mint Classics’ storage facilities.
Order Details: Tracks the specifics of each customer order.
Orders: Contains details about customer orders, including dates and statuses.
Payments: Records payment transactions made by customers.
Customers: Stores customer contact and account information.
Employees: Contains employee details, job titles, and relationships with customers.
Offices: Holds information about Mint Classics' office locations.
Product Lines: Group similar products into categories.
Files and Folders
The following files and folders are included in this project:

Queries
This folder contains SQL queries used for exploratory data analysis (EDA) across various clusters of the Mint Classics database:
Customers_Analysis.sql: SQL queries to analyze customer data.
Employees_Analysis.sql: SQL queries to examine employee and managerial structures.
Inter_Views_Anaysis.sql: SQL queries to analyze relationships across products, customers, and employees.
Products_analysis.sql: SQL queries focusing on product performance, inventory, and sales.
Views
This folder contains SQL scripts that create views combining data from multiple tables for in-depth analysis:

All_Views.sql

SQL script creating a view that links customer, order, and payment data.
SQL script creating a view that analyzes employee roles, office locations, and customer management.
SQL script creating a view that combines data from products, warehouses, and order details.
Mint_classic_DB_Model.mwb
A MySQL Workbench model file, which includes the database schema and an Extended Entity Relationship (EER) diagram.

README.md
This file provides an overview of the project, the dataset, and the included files.

Key Findings
Warehouse Optimization: According to stock levels and inventory turnover, Warehouse D is the most likely candidate for closure, whilst Warehouse B is the most profitable and well-stocked.
Product Management: Certain items, such as the 1985 Toyota Supra, have a large inventory but low sales and should be discontinued, whilst high-demand products, such as the 1968 Ford Mustang, should be prioritized for restocking.
Customer Retention: Key customers, such as Euro+ Shopping Channel, should be retained, and there are prospects for growth in lagging regions like Tokyo and Sydney.
Sales Representative Performance: While some reps, such as Gerard Hernandez and Leslie Jennings, thrive in generating revenue, others may need further training or reassignment to improve their performance.
