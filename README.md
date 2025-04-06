# Freddy's BI-Cycle Power BI Dashboard Project

This Power BI project presents a comprehensive and interactive Business Intelligence (BI) solution for **Freddy's BI-Cycle**, focusing on five key areas: **Sales**, **Sales Over Time**, **HR**, **Inventory**, and **Finance**.

The dashboards provide a 360-degree view of Freddy's operational and strategic performance using real-time insights, clean visualizations, and actionable KPIs.

---

## Project Overview

**Goal**  
To enable data-driven decision-making for stakeholders by providing insights into:

- Revenue & margin trends  
- Inventory performance  
- Financial budget vs actuals  
- Employee structure and turnover  
- Global and product-level sales analysis  

## What I Did

This project follows a complete Business Intelligence workflow using Power BI:

1. **Data Extraction**  
   - Extracted datasets from a **remote SQL-based database** using direct query and SQL scripts.
   - Exported and saved the relevant data tables into **CSV format** for external processing.

2. **Data Transformation**  
   - Cleaned and transformed the raw datasets using **Power Query Editor**.
   - Standardized date formats, removed duplicates, split complex columns, and handled nulls.

3. **Data Modeling**  
   - Designed and implemented a **Star Schema** in Power BI:
     - Created fact tables (e.g., sales, financials) and dimension tables (e.g., product, date, employee).
     - Defined relationships between tables to support accurate slicing and dicing.
     - Created calculated columns and DAX measures to enable advanced analysis (e.g., YTD, R12, margins, budget variance).

4. **Dashboard Building & Visualization**  
   - Built multiple interactive dashboards with slicers, charts, tables, and maps.
   - Implemented filters for time, currency, product, department, and geography.
   - Designed dashboards with end users in mind for clarity and usability.

## Dashboards Breakdown

### 1. Sales Insight

- Total Revenue, Orders, Cost, and Margin over years  
- Product Category breakdown  
- Margin % by product  
- Sales trends using R12, YTD, and Total Revenue  

**Screenshot:**  
![Sales Insight](https://github.com/fuzzyzester/powerbi_visualization_project/blob/main/Sales%20Insight.png)

---

### 2. Sales Over Time

- Daily Averages for Sales, Orders, Cost, and Margin  
- Revenue by:
  - Geography (Map View)
  - Country & Continent
  - Color Segmentation  
- Currency toggle (USD, EUR, etc.)

**Screenshot:**  
![Sales Over Time](https://github.com/fuzzyzester/powerbi_visualization_project/blob/main/Sales%20Overtime.png)

---

### 3. HR Dashboard

- Active Employee count, turnover, and average tenure  
- Organization hierarchy visualization  
- Department filter and employee search  
- Employee details: age, tenure, job title  
- Revenue by geography for workforce insights  

**Screenshot:**  
![HR Dashboard](https://github.com/fuzzyzester/powerbi_visualization_project/blob/main/HR%20Dashboard.png)

---

### 4. Product Inventory

- Inventory KPIs:
  - Total Inventory Value  
  - Unique Products  
  - Average Inventory Value  
  - Inventory Turnover Rate  
- Stock-out Orders by Product Category  
- Year-over-Year Inventory comparison  
- Top 5 Products by Inventory Value  

**Screenshot:**  
![Product Inventory](https://github.com/fuzzyzester/powerbi_visualization_project/blob/main/Product%20Inventory.png)

---

### 5. Finance (Chart of Accounts)

- Budget vs Actuals across GL accounts  
- Monthly and YTD difference tracking  
- Drill-down into revenue, cost, and OPEX  
- Trial Balance with variance calculations  

**Screenshot:**  
![Finance Dashboard](https://github.com/fuzzyzester/powerbi_visualization_project/blob/main/ChartofAccounts.png)

---

## Tools Used

- Power BI Desktop  
- DAX for KPIs and custom measures  
- Power Query for data transformation  
- Card visuals, pie charts, bar graphs, matrix tables, and maps  

---

## Key Highlights

- Drill-down capabilities from summary KPIs to granular data  
- Custom slicers for Time, Currency, Products, and Departments  
- Yearly trend insights via R12 and YTD metrics  
- Performance monitoring of top and underperforming products  
- Employee organizational structure visualization  
- Finance dashboard resembling a real-world chart of accounts 
