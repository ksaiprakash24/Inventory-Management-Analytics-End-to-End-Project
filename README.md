# 📦 Inventory Management Analytics | End-to-End Data Analytics Project

## 📌 Project Overview

This project demonstrates a complete end-to-end Data Analytics workflow using Excel, Python (Pandas), SQL Server, and Power BI.

The project begins with raw inventory and sales data stored in Excel, which is processed using Python and loaded into SQL Server. SQL is then used to perform data analysis, create reporting tables, and build views. Finally, the processed data is imported into Power BI to create an interactive dashboard for business insights.

---

# 🚀 Tech Stack

- Microsoft Excel
- Python
- Pandas
- SQLAlchemy
- PyODBC
- SQL Server
- SQL (T-SQL)
- Power BI
- DAX

---

# 📂 Dataset

The source dataset contains two worksheets:

### Sales Data
- Customer Orders
- Revenue
- Costs
- Warehouse
- Products
- Order Quantity

### Inventory Stock Control
- Inventory Value
- Stock Quantity
- Vendors
- Reorder Levels
- Sales Price
- Stock Location

---

# 🔄 End-to-End Workflow

```text
CMD
↓
Install Required Libraries
↓
Excel
↓
Source Data
↓
SQL Server
↓
Create Database (InventoryDB)
↓
Python (Pandas)
↓
Read Excel Sheets
↓
SQLAlchemy Engine
↓
Create Raw Tables
↓
SQL Server
↓
SQL Analysis
↓
Views
↓
Reporting Tables
↓
Power BI
↓
Import Data
↓
Relationships
↓
DAX Measures
↓
Dashboard Development
```

---

# 🗄 SQL Server Objects

## Raw Tables

- SalesData
- InventoryStockControl

---

## SQL View

- vw_TotalRevenueByWarehouse

---

## Reporting Tables

- CustomerTypeSummary
- WarehouseSummary
- MonthlySalesSummary
- VendorSummary

---

# 📖 SQL Concepts Used

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- Aggregate Functions
- CASE Statements
- INNER JOIN
- Common Table Expressions (CTE)
- Window Functions
- SQL Views
- Reporting Tables

---

# 📊 Power BI Features

- Interactive Dashboard
- KPI Cards
- DAX Measures
- Time Intelligence
- Slicers
- Tables
- Clustered Column Charts
- Clustered Bar Charts
- Line Charts
- Donut Charts
- Treemap
- Professional Layout
- Navigation Buttons

---

# 📈 Dashboard Pages

## Overview Dashboard

![Overview Dashboard](Screenshots/Dashboard_Page1.png)

## Inventory & Stock Analysis Dashboard

![Inventory Dashboard](Screenshots/Dashboard_Page2.png)

Business Performance Dashboard

Features:

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Revenue Per Warehouse
- Revenue By Customer Type
- Revenue Trend
- Top Customers

---

## Dashboard Page 2

Inventory Analysis Dashboard

Features:

- Inventory Value
- Stock Quantity
- Vendor Analysis
- Inventory Distribution
- Average Sales Price
- Item Discontinued Analysis

---

# 📌 DAX Measures

The project includes 30+ DAX measures organized into folders.

### Customers
- Average Orders Per Customer

### Inventory
- Total Inventory Value
- Total Stock Quantity
- Average Sales Price
- Average Cost Per Item
- Maximum Stock
- Minimum Stock

### KPIs
- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Total Quantity
- Average Revenue
- Average Order Value
- Profit Margin %

### Orders
- Average Unit Price
- Average Quantity Per Order

### Reorder
- Average Reorder Level
- Average Days Per Reorder
- Average Reorder Quantity
- Low Stock Items

### Revenue
- Highest Revenue
- Lowest Revenue
- Revenue Per Customer
- Revenue Per Order

### Time Intelligence
- Revenue MTD
- Revenue QTD
- Total Revenue YTD
- Previous Month Revenue
- Previous Year Revenue

### Warehouse
- Revenue Per Warehouse
- Warehouse Count

---

# 📷 Dashboard Preview

## Dashboard Page 1

![Overview Dashboard](Screenshots/Dashboard_Page1.png)

---

## Dashboard Page 2

## Inventory & Stock Analysis Dashboard

![Inventory Dashboard](Screenshots/Dashboard_Page2.png)

---

# 📁 Project Structure

```
Inventory-Management-Analytics
│
├── Data
│   └── Inventory Management Data Model.xlsx
│
├── Jupyter Notebook
│   └── Inventory Project.ipynb
│
├── SQL
│   ├── Day1.sql
│   ├── Day2.sql
│   ├── Day3.sql
│   ├── Day4.sql
│   ├── Day5.sql
│   ├── Day6.sql
│   ├── Day7.sql
│   ├── Day8.sql
│   ├── Day9.sql
│   ├── Day10.sql
│   └── Day11.sql
│
├── Power BI
│   └── Inventory Management Dashboard.pbix
│
├── Dashboard Screenshots
│   ├── Dashboard Page 1.png
│   └── Dashboard Page 2.png
│
└── README.md
```

---

# 🎯 Key Learnings

- Built an end-to-end data analytics solution.
- Processed Excel data using Python (Pandas).
- Loaded data into SQL Server using SQLAlchemy.
- Performed SQL analysis using multiple SQL concepts.
- Created SQL Views and Reporting Tables.
- Connected SQL Server to Power BI.
- Developed an interactive Power BI dashboard using DAX measures and professional visualizations.

---

# 👤 Author

**Sai Prakash K**

Data Analyst | SQL | Python | Power BI | Excel
