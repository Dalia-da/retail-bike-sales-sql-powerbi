# Retail Bike Sales - SQL, Excel & Power BI Analysis

SQL, Excel & Power BI analysis of retail bike sales for a multi-store bicycle retailer (public training dataset).

## Overview
End-to-end retail sales analysis: a multi-table SQL query pulls order-level data from the source database, which is then explored in Excel and visualized in an interactive Power BI dashboard.

## Tools
- SQL Server (multi-table joins)
- Excel (Pivot Tables)
- Power BI (line, map, column, pie, clustered bar, and treemap visuals)

## Key Additions
- Wrote a 7-table SQL join (customers, orders, order items, products, categories, brands, stores, staff) to extract a flattened, order-level dataset from the database.
- Added an independent "Order Insights" page in Power BI with new DAX measures (Average Order Value) and a sales-rep revenue ranking.
- Identified that the Road Bikes category had zero sales in 2016 before growing to $1.16M in 2017.

## Files
- `Query.sql` — SQL query used to extract the dataset
- `BikeStores Dashboard.xlsx` — Excel data and pivot tables
- `Bikestores Dashboard.pbix` — Power BI report
