# Sales-Analytics-Report-Data-Model-Star-Schema-
Sales Analytics Report (Data Model – Star Schema) is an interactive Power BI dashboard designed to analyze and visualize sales performance across various dimensions such as product, time, geography, and promotion. 

## 🧾 Overview

This project presents a dynamic and interactive **Sales Data Analysis Dashboard** built using **Power BI**. It enables business stakeholders to monitor performance, evaluate trends, and gain data-driven insights using a visually rich interface.

The dashboard uses a **Star Schema** data model for efficient data organization and query performance.

---

## Business Requirements

1) Top/Bottom 5 product by Sales/Profit/Quantity Sold.

2) How do sales trends vary over time (daily, monthly, quarterly, annually) ?

3) Show relationship between sales & profit.

4) Compare sales/profit/quantity sold between any two periods selected by the user.

5) Average discount offered in each discount category.

6) Total number of orders.

7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product/Date/Customer ID/Promotion Categories)

8) Show sales by different cities.

##  Key Analytical Objectives

### 1. Top/Bottom Performing Products
- Identify **Top/Bottom 5** products based on:
  -  Total Sales  
  -  Profit  
  -  Quantity Sold  

### 2. Sales Trend Analysis
- Analyze sales performance across:
  -  Daily  
  -  Monthly  
  -  Quarterly  
  -  Yearly  

### 3. Sales vs. Profit Correlation
- Visualize the relationship between **Sales** and **Profit** using scatter plots and trendlines.

### 4. Comparative Period Analysis
- Compare **Sales**, **Profit**, and **Quantity Sold** between any **two user-defined time periods**.

### 5. Discount Analysis
- Calculate and visualize the **average discount** per discount category.

### 6. Total Orders
- Display the **total number of orders** in the dataset.

### 7. Detailed Order Breakdown
- Show all major fields per order including:
  - Sales  
  - Profit  
  - Discount  
  - Net Sales  
  - And more  
- Allow filtering by:
  - Product  
  - Date  
  - Customer ID  
  - Promotion Category  

### 8. City-wise Sales
- Visualize **sales by city** using maps or bar charts.

---

##  Data Model Structure

This project is built on a **Star Schema** structure:

**Fact Table**
- `Sales_Fact`

**Dimension Tables**
- `Date`
- `Customer`
- `Product`
- `Promotion`
- `Geography`

  ##  Tools Used

- Power BI Desktop  
- Power Query (ETL)  
- DAX (Data Analysis Expressions)  
- Star Schema Modeling  

---
## Dashboad 

<img width="1309" height="732" alt="01" src="https://github.com/user-attachments/assets/55042e22-9406-4d2e-b2eb-c1c2e2c20207" />

<img width="1310" height="735" alt="Screenshot 2025-07-16 185126" src="https://github.com/user-attachments/assets/d46147ec-cb20-4812-9ba7-b98d5bf80345" />

<img width="1315" height="729" alt="Screenshot 2025-07-16 185154" src="https://github.com/user-attachments/assets/3184dd12-67b4-4652-b64d-b157d90ad944" />

<img width="1309" height="726" alt="Screenshot 2025-07-16 185212" src="https://github.com/user-attachments/assets/2c42e726-e2b7-41b7-86c7-c173ac3e665a" />

<img width="1304" height="730" alt="Screenshot 2025-07-16 185241" src="https://github.com/user-attachments/assets/cf77cc8b-6ff4-4819-876b-680783cddeba" />


