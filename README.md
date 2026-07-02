# Adventure Works Sales Analytics Dashboard

Built an end-to-end sales analytics solution for Adventure Works Cycles, 
a multinational bicycle manufacturer, using Power BI, Power Query, and DAX.

## What I did
- Consolidated two Internet Sales fact tables (~60,000 transactions) 
  into a single unified fact table
- Enriched sales data via lookups: product name, unit price, and 
  customer full name from dimension tables
- Built a custom date hierarchy from Order Date (Year, Month, Quarter, 
  Financial Month/Quarter, Weekday) to support time-intelligence analysis
- Calculated Sales Amount, Production Cost, and Profit using DAX measures
- Designed a Star Schema data model (1 fact table, 5 dimension tables: 
  Customer, Product, Product Category, Product Subcategory, Sales Territory)
- Built interactive Power BI dashboards: year-wise sales (bar chart), 
  month-wise trend (line chart), quarter-wise split (pie chart), 
  and a combo chart comparing Sales vs. Production Cost
- Added KPIs for performance by Product, Customer, and Region

## Tools
Power BI · Power Query · DAX · Excel · Data Modeling (Star Schema)

## Dashboard
