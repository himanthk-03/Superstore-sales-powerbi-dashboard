# Superstore Sales Performance Dashboard (Power BI)

Interactive Power BI dashboard analyzing sales, profit, discounts and
shipping for a US retail company (9,994 orders, 2014-2017).

## Tools
Power BI Desktop, Power Query, DAX

## Dataset
Sample Superstore dataset (Kaggle), included as Sample_-_Superstore.csv

## What I did
- Cleaned and transformed the data in Power Query (date locale fix, data types, text trimming, Shipping Days and Product Key columns)
- Built a data model with a custom date table and dimension tables
- Wrote 15+ DAX measures (YoY growth, YTD, profit margin, and more)
- Built a 5-page interactive dashboard with slicers, drill-through, tooltips and navigation

## Key insights (2017)
- Technology and Office Supplies earn 97% of profit; Furniture's margin is only 1.4%
- Tables, Machines, Supplies and Bookcases lose money
- Discounts above 20% lost $48K, while no discount and 11-20% earned $104K and $34K
- West leads with a 17.5% margin; Central is weakest at 5.1%
- Standard Class shipping takes about 5 days, against 2.2 for First Class

## Screenshots
![Executive Summary](screenshots/01_executive_summary.png)
![Products and Customers](screenshots/02_products_customers.png)
![Geography](screenshots/03_geography.png)
![Discount and Shipping](screenshots/04_discount_shipping.png)
![Key Insights](screenshots/05_key_insights.png)

## Files
- Superstore_Sales_Dashboard.pbix: open with Power BI Desktop
- Superstore_Sales_Dashboard.pdf: static export of the report
