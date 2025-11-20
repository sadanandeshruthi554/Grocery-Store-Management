# Grocery-Store-Management
### 📌 Overview

- I built a Grocery Store Management System using SQL to organize and manage all grocery store operations. This system stores information about customers, employees, suppliers, products, categories, orders, and        order details in a structured and secure way.

- The aim of this project is to simplify daily tasks like inventory tracking, order management, sales monitoring, and performance analysis.
---------
### 🎯 Objectives

- Create a centralized SQL database for all store records
- Manage customers, suppliers, employees, products, and categories
- Track orders, sales, and inventory levels
- Improve data accuracy and store efficiency
- Generate useful business insights for decision-making.
----------
### 🗂️ Database Schema

*My project consists of the following main tables:*

### 1. Customers:

- CustomerID
- Name
- Contact
- Email
- Address

### 2. Suppliers:

- SupplierID
- Name
- Contact
- Address

### 3. Employees:

- EmployeeID
- Name
- Role
- Contact

### 4. Categories:

- CategoryID
- CategoryName

### 5. Products:

- ProductID
- Name
- CategoryID
- SupplierID
- Price
- StockQty

### 6. Orders:

- OrderID
- CustomerID
- EmployeeID
- OrderDate
- TotalAmount

### 7. OrderDetails:

- OrderDetailID
- OrderID
- ProductID
- Quantity
- PriceEach

- The database uses primary keys, foreign keys, and relationships to maintain consistency and integrity.
------
### 🛠️ Tools & Technologies Used

- MySQL / PostgreSQL / SQL Server (any SQL database)
- SQL Workbench / pgAdmin / SSMS (for query execution)
- Draw.io / Lucidchart (for ER diagram design)
- Excel / CSV files (for sample data loading)
----------
### 🔍 Key Features

- Manage customers, suppliers, and employees
- Track product categories and stock
- Store order details and transaction records
- Generate sales summaries and customer patterns
- Analyze employee and supplier performance
- View monthly revenue and order trends
----------
### 🚀 How to Run

#### 1. Install MySQL 8+ (or MariaDB).
#### 2. Create a new database for this project:

   CREATE DATABASE GROCERY_STORE;
USE GROCERY_STORE;
#### 3. Copy and run the script from GROCERY_STORE_PROJECT.sql (or your schema + insert file) into your SQL client.
- MySQL 8+ is recommended for best compatibility.

#### 4. Explore the queries step by step:
- Section A: Basic SQL filters (WHERE)
- Section B: Joins & Subqueries (Customers, Products, Orders, Suppliers)
- Section C: Aggregations & Grouping (GROUP BY, HAVING)
- Section D: Advanced SQL

  - CTEs
  - Window Functions
  - Views
  - Employee & Supplier Performance Queries
  - Revenue Analysis Queries
-----------
### 📊 Main Analysis Performed

- Unique customers and top buyers
- Best-selling and high-revenue products
- Monthly order and revenue trends
- Supplier contribution to product sales
- Employees handling the highest sales
- Quantity vs Total price relationship
-------------
### 💡 Key Insights

- A small group of customers brings high revenue
- Best-selling items need more stock
- Certain months show higher order volume
- Few suppliers dominate product distribution
- Some employees manage most orders
- Total order value rises with quantity
--------------
### 📝 Recommendations

- Launch customer loyalty programs
- Promote slow-moving products
- Maintain safety stock for fast-selling items
- Improve supplier coordination
- Use SQL-based reports for weekly planning
-------------
### ✅ Conclusion

- The Grocery Store Management System helps automate store activities, reduce manual work, and provide accurate insights. SQL makes it easier to track products, customers, sales, and inventory—leading to better decision-making and efficient store operations.
----------
### 🔗 Live Dashboard
- you can download the .pbix file from this repository and view it in Power BI Desktop.
- 👩‍💻 About Me
   - SADANANDE SHRUTHI
   - Aspiring Data Analyst
   - Skilled in Power BI, Python, SQL, EDA, and Statistics
   - Linkdin :www.linkedin.com/in/sadanande-shruthi-630597256
