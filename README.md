# Sales Analytics Capstone Project – Northwind Traders

This Sales Analytics capstone project uses the Northwind Traders dataset to build an interactive Power BI dashboard. It analyzes sales performance, customer behavior, inventory trends, and employee efficiency using a MECE framework to support data-driven business decisions.

## Project Overview
This Sales Analytics capstone project focuses on building an interactive Power BI dashboard using the Northwind Traders dataset to analyze key business operations in a wholesale environment. The project aims to uncover insights related to sales performance, customer behavior, inventory efficiency, supplier contribution, and employee performance.

A structured MECE (Mutually Exclusive, Collectively Exhaustive) business framework is applied to ensure comprehensive analysis without overlapping metrics. By integrating data from multiple relational tables and enabling interactive exploration through filters and visuals, the dashboard supports data-driven decision-making and helps stakeholders monitor performance, identify trends, and improve operational efficiency.


## Dataset Description
Dataset Description
The Northwind database contains the sales data for a fictitious company called “Northwind Traders,” which imports and exports specialty foods from around the world

Table Explanations
Customers Table
This table stores information about the company's customers. It includes fields for customer ID, company name, contact name, contact title, address, city, region, postal code, country, phone, and fax.

Employees Table
This table stores information about the company's employees. It includes fields for employee ID, last name, first name, title, title of courtesy, birth date, hire date, address, city, region, postal code, country, home phone, extension, photo, notes, reports to, and photo path.

Orders Table
This table stores information about the company's orders. It includes fields for order ID, customer ID, employee ID, order date, required date, shipped date, ship via, freight, ship name, ship address, ship city, ship region, ship postal code, and ship country.

Order Details Table
This table stores detailed information about the items within each order. It includes fields for order ID, product ID, unit price, quantity, and discount.

Products Table
This table stores information about the company's products. It includes fields for product ID, product name, supplier ID, category ID, quantity per unit, unit price, units in stock, units on order, reorder level, and whether the product is discontinued.

Suppliers Table
This table stores information about the company's suppliers. It includes fields for supplier ID, company name, contact name, contact title, address, city, region, postal code, country, phone, fax, and home page.

Shippers Table
This table stores information about the company's shipping companies. It includes fields for shipper ID, company name, and phone.

Categories Table
This table stores information about the product categories. It includes fields for category ID, category name, and description.


## MECE Business Framework
This project follows a MECE (Mutually Exclusive, Collectively Exhaustive) business framework to ensure complete coverage of business operations without overlapping metrics.

### 1. Sales & Order Performance
- Total Sales and Order Count  
- Sales Trends over Time  
- Average Order Value  
- Discount and Freight Cost Impact  
- Order Processing and Delivery Time  

### 2. Customer Insights
- Total Customers  
- New vs Repeat Customers  
- Sales by Customer  
- Customer Geography  
- Top Customers by Revenue  

### 3. Product & Inventory Management
- Product and Category-wise Sales  
- Units in Stock vs Reorder Level  
- Fast and Slow-Moving Products  
- Units on Order  
- Discontinued Product Impact  

### 4. Supplier & Logistics Analysis
- Number of Active Suppliers  
- Products per Supplier  
- Supplier-wise Sales Contribution  
- Supplier Geography  
- Shipper-wise Freight and Orders  

### 5. Employee Performance
- Sales by Employee  
- Orders by Employee  
- Average Sales per Order  
- Regional Performance  
- Tenure vs Performance  

## Dashboard Features
- Interactive KPI cards and charts  
- Dynamic slicers for date, category, country, and employee  
- Drill-down and cross-filtering for deeper analysis  

## Tools & Technologies
- Power BI  
- DAX  
- SQL
- Excel    

## Project Outcome
The dashboard provides a consolidated and interactive view of Northwind Traders’ operations, enabling stakeholders to identify trends, optimize performance, and make informed strategic decisions.
