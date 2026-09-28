# FMCG Sales Analysis Dashboard

## 📊 Project Overview

This project presents an interactive FMCG Sales Analysis Dashboard created using Microsoft Power BI. The dashboard analyses sales, profit, units sold, orders, products, categories, sales channels and state-wise performance.

The project uses an Excel dataset containing sales transactions along with supporting information about products, distributors, retailers and customers. Interactive slicers are provided to filter the analysis and explore business performance from different perspectives.

---

## 🎯 Objectives

- Monitor total sales, profit, units sold, orders and profit margin.
- Analyse monthly sales trends.
- Compare different sales channels.
- Identify high-performing product categories and products.
- Analyse state-wise sales performance.
- Create an interactive dashboard for quick business analysis.

---

## 🗂️ Dataset

**Dataset File:** `FMCG_Sales_Dataset_project_1.xlsx`

### Dataset Details

- Data Source: Excel Workbook
- Number of Sheets: 9
- Total Transactions: 4,000
- Data Period: January 2025 – December 2026
- Domain: FMCG Sales

### Main Tables / Data Areas

- Sales
- Product
- Distributor
- Retailer
- Customer
- Date
- Sales Target
- Inventory

### Important Sales Fields

- Order_ID
- Date
- Product_ID
- Manufacturer_ID
- Distributor_ID
- Retailer_ID
- Customer_ID
- Quantity
- Unit_Selling_Price
- Discount_Percent
- Net_Sales
- Total_Cost
- Profit
- Payment_Mode
- Sales_Channel

---

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Microsoft Excel
- Power Query
- DAX

---

## 🔄 Methodology

### 1. Data Import
The Excel workbook was imported into Power BI.

### 2. Data Cleaning
Data types, fields and values were checked and prepared for analysis.

### 3. Data Modelling
The Sales table was used as the main transaction table along with supporting business information.

### 4. DAX Measures
Important measures were created to calculate sales, profit, units, orders and profit margin.

### 5. Dashboard Creation
KPI cards, charts, map visuals and slicers were used to create an interactive dashboard.

---

## 📐 DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Sales[Net_Sales])
