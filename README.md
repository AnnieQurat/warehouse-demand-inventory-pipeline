# Warehouse Demand & Inventory Pipeline

**Status: in progress (started November 2026)**

## Goal
Use public warehouse sales data to forecast demand, rank items by value (ABC analysis) and monitor data quality, with a reusable template that small businesses can run on their own sales files.

## Data
Montgomery County, Maryland: warehouse and retail sales (public open data).
Source: [https://catalog.data.gov/dataset/warehouse-and-retail-sales]
The original file is in `data/raw/` and is never edited.

## Plan
- 1. First look at the data in Excel 
- 2. Data-quality checks (missing values, duplicates, odd values)
- 3. Clean data and load it into PostgreSQL
- 4. ABC analysis (which items matter most)
- 5. Demand forecast (simple baseline first)
- 6. Power BI dashboard
- 7. Reusable template and documentation

## Tools
Python, PostgreSQL, Power BI, Excel

## Author
Annie Qurat
