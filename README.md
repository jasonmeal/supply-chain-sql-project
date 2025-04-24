# 🧠 Supply Chain SQL + Tableau Analytics Project

This project simulates a multi-warehouse retail supply chain operation. I used SQL to model and analyze data across product sales, inventory levels, and profitability. The results were visualized using Tableau to create a dynamic dashboard highlighting key supply chain KPIs.

---

## 🔧 Tools Used

- **SQLite** for database design and querying
- **Tableau Public** for interactive data visualization
- **CSV / Excel** for simulated data input
- **GitHub** to document and showcase the project

---

## 📂 Data Tables

- `products`: catalog of items with categories, cost, and price
- `warehouses`: locations and regions of inventory storage
- `inventory`: current stock levels across products and warehouses
- `sales`: transaction-level data with date, product, and quantity sold
- `suppliers`: vendors linked to products
- `reorders`: order records triggered by low stock

---

## 🔍 Key SQL Queries

- 📦 **Top Selling Products by Category**
- 📈 **Monthly Sales Trends**
- 🔄 **Inventory Turnover Rate**
- 🚨 **Low Inventory Alerts**
- 💰 **Profitability by Product**

All queries were written in SQL and tested using **DB Browser for SQLite**. Results were exported as CSV files and connected to Tableau.

---

## 📊 Tableau Dashboard Overview

The Tableau dashboard displays:

| Metric                      | Visualization Type         |
|----------------------------|----------------------------|
| Monthly Sales by Category  | Line Chart or Stacked Bars |
| Inventory Turnover Rate    | KPI Indicator or Bar Chart |
| Low Inventory Products     | Color-coded Table          |
| Profitability by Product   | Bar Chart by Profit Margin |

Filters include:  
- 🏢 Warehouse  
- 📅 Date Range  
- 🎯 Product Category  

> 📍 **View the live dashboard (hosted on Tableau Public)**  
> 🔗 *[Insert your Tableau Public link here once published]*

---

## 🚀 How to Recreate This Project

1. Use `data/` folder to import CSVs into your SQL environment
2. Run the queries in the `sql/` folder
3. Export results and load into Tableau
4. Create interactive visualizations using drag-and-drop features
5. Publish your dashboard to Tableau Public for public access

---

## 📁 Project Structure

---

**Created by Jason Meal**
