# Freshco Sales Analysis (Excel Dashboard)

This project is an Excel-based sales analysis for Freshco Hypermarket, a retail store that launched home delivery services in HSR Layout, Bangalore. The goal was to explore sales performance, delivery efficiency, and customer behavior using pivot tables, charts, and slicers.

All analysis was done using Microsoft Excel with a focus on user-friendly dashboards and interactive visualizations.

---

## Project Description

The project involved analyzing raw transaction-level sales data to derive business insights. Key focus areas include order trends, revenue breakdowns, completion status, customer ratings, and delivery times. The output is a clean, interactive dashboard in Excel that helps decision-makers view performance metrics quickly.

---

## ETL Process (Extract, Transform, Load)

### 1. Extract
- Imported raw transactional data from the `Freshco_Raw_data.xlsx` file.
- The dataset included order-level information such as product amount, delivery date, order date, source, ratings, and discounts.

### 2. Transform
Data cleaning and transformation were performed in Excel using Power Query and formulas:
- Removed null values and irrelevant rows.
- Standardized date columns (`Order Date`, `Delivery Date`) into a consistent format.
- Created calculated columns:
  - **Delivery Time**: Delivery date minus order date.
  - **Revenue After Discount**: Product amount minus discount.
  - Extracted **Month**, **Day**, and **Weekday** from order date.
- Cleaned inconsistent source names.
- Ensured all data types (dates, numbers, text) were properly formatted.

### 3. Load
- Loaded the transformed data into pivot tables for analysis.
- Created interactive dashboards using pivot charts and slicers.
- Used slicers for filtering by source, month, and order status.
- Final result is presented in `Freshco_sales_analysis.xlsx`.

---

## Key Insights

### Order Performance
- Visualized order completion status using a donut chart.
- Analyzed revenue trends by month, day, and source.
- Displayed revenue contribution from different customer acquisition sources.

### Product Performance
- Listed top 10 products based on revenue.
- Used slicers for filtering revenue by product and source.

### Customer Analysis
- Calculated average customer rating by source.
- Displayed source-wise customer distribution.
- Measured average revenue per order grouped by source.

### Delivery Efficiency
- Calculated average delivery time by month and weekday.

---

## Tools Used
- Microsoft Excel
- Pivot Tables
- Pivot Charts (Donut, Line, Bar, Column)
- Power Query
- Slicers for interactive filtering

---

## Files Included
- `Freshco_Raw_data.xlsx`: Original transactional dataset.
- `Freshco_sales_analysis.xlsx`: Processed data, pivot tables, and dashboards.

---

Created by: [vikask011](https://github.com/vikask011)
