# global-superstore-dashboard-excel
Interactive Excel dashboard analysing 51K+ global retail transactions using PivotTables, PivotCharts, calculated fields, and slicers to surface sales, profit, and discount trends.
Global Superstore Sales Analysis Dashboard

An interactive Excel dashboard built from the Global Superstore dataset found on Kaggle, with 51,290 transaction records covering sales, profit, discounts, and shipping across global regions.

What this project includes:

Data cleaning: Fixed date formatting/encoding issues, removed redundant fields, validated for duplicates
Calculated columns: Profit Margin, Shipping Days, Discount Tier, Order Month-Year, Profitable (Y/N)
4 PivotTables analysing: Sales & Profit by Region/Category, monthly sales trends by year, top 10 products by sales, and discount vs. profit correlation by sub-category
PivotCharts (clustered column, line, and combo charts) plus a ranked table for top products
A single-page interactive Dashboard with KPI cards (total sales, total profit, profit margin, distinct order count) and cross-connected slicers (Region, Category, Year)

Key insights found:
The West region generated the highest profit margin despite not having the highest sales volume 
Sub-categories with discounts above 30% saw profit turn negative
The Central Region is the region with the highest number of sales

Tools used: Microsoft Excel (PivotTables, PivotCharts, Power Query, Slicers, IFS/nested formulas)
