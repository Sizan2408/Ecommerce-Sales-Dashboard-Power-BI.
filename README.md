# Ecommerce Store Sales Dashboard 📊

## Overview  
This Power BI dashboard analyzes Ecommerce sales, profit, and customer behavior using interactive visuals and DAX calculations.  

## Features  
- Sales breakdown by category & sub-category  
- Customer analysis (top buyers)  
- Sales distribution by payment mode  
- Geographical insights (sales by states & cities)  

## DAX Functions Used  
- **Total Sales:** `SUM(data[Total Sales])`  
- **Profit Margin (%):** `DIVIDE(SUM(data[Profit]), SUM(data[Total Sales])) * 100`  
- **Previous Month Sales:** `CALCULATE(SUM(data[Total Sales]), PREVIOUSMONTH(data[Date]))`  
- **Top 5 Customers:** `RANKX(ALL(data[Customer Name]), SUM(data[Total Sales]), , DESC, DENSE)`  

## Screenshots  
[Dashboard Preview]([Screenshot 2025-03-04 035344](https://github.com/user-attachments/assets/3952c127-7abb-4192-ae0f-eb951daf9162)
)  

## How to Use  
1. Download the `.pbix` file.  
2. Open it in **Power BI Desktop**.  
3. Connect your data source (if needed).  

## Connect With Me  
Let's discuss and improve our Power BI skills.  
[LinkedIn](www.linkedin.com/in/sahanur-asif-sizan)  

---

