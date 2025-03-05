# Ecommerce Store Sales Dashboard 📊

## Dashboard Link :https://app.powerbi.com/groups/me/reports/e9fd4a8c-2a13-4a82-b21a-01b4fee4a3df?ctid=2668b5d0-7189-40cd-a301-d607a36fb212&pbi_source=linkShare

## Overview  
This project is an interactive Power BI dashboard that provides insights into Ecommerce sales performance. It helps businesses track total sales, profit, quantity sold, and key customer trends.The dashboard enables data-driven decision-making by visualizing important metrics and patterns.
## Features  
- ✅ Total Sales, Profit & Quantity Overview
- ✅ Sales Breakdown by Category & Sub-Category
- ✅ Customer Insights – Top Buyers & Sales Distribution
- ✅ Payment Mode Analysis – Understanding Customer Preferences
- ✅ Geographical Sales Insights – Performance by States & Cities
- ✅ DAX-Powered Metrics & KPIs for Business Intelligence

## DAX Functions Used  
- **Total Sales:** `SUM(data[Total Sales])`  
- **Profit Margin (%):** `DIVIDE(SUM(data[Profit]), SUM(data[Total Sales])) * 100`  
- **Previous Month Sales:** `CALCULATE(SUM(data[Total Sales]), PREVIOUSMONTH(data[Date]))`  
- **Top 5 Customers:** `RANKX(ALL(data[Customer Name]), SUM(data[Total Sales]), , DESC, DENSE)`

## Tools & Technologies Used
- Power BI – Data Visualization & Business Intelligence
- DAX (Data Analysis Expressions) – Custom calculations & measures
- Power Query – Data transformation & modeling
- Excel/CSV Dataset – Source data for visualization


## Screenshots  
![Dashboard Preview](![Screenshot 2025-03-04 035344](https://github.com/user-attachments/assets/cce41cfa-2d28-4f44-919c-12b72caaad3d)
) 

## How to Use  
1. Download the `.pbix` file.  
2. Open it in **Power BI Desktop**.  
3. Connect your data source (if needed).  

## Connect With Me  
Let's discuss and improve our Power BI skills.  
[LinkedIn](https://www.linkedin.com/in/sahanur-asif-sizan)  
[Email](sasifsizan2408@gmail.com)

