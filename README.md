# Retail-Sales-Performance-Dashboard
## Project Objective
- Analyze retail business performance across transactions, products, customers, and stores
- Build an interactive Power BI dashboard to monitor key metrics and support data-driven decision-making
- Identify trends, patterns, and opportunities to improve sales performance and operational efficiency
## Data Source
The dataset used in this project was obtained from [Xóm Data Playground](https://www.xomdata.com/d%E1%BB%B1-%C3%A1n-theo-l%C4%A9nh-v%E1%BB%B1c/b%C3%A1n-l%E1%BA%BB).
## Key Questions / KPIs
- What is the total revenue, total orders, and average order value (AOV)?
- How do sales perform over time (monthly/seasonal trends)?
- Which products and categories generate the highest revenue?
- Who are the top customers and what are their purchasing behaviors?
- How do different stores/regions perform in terms of sales and growth?
- What are the key KPIs: Revenue, Quantity Sold, Number of Orders, AOV, Growth Rate?
## Process
- Data Preparation: Data was imported from a SQL source and processed in Microsoft Power BI. The dataset was cleaned and transformed by handling missing values, removing duplicates, and standardizing formats.
- Data Modeling: A star schema was designed with a central fact table (fact_sales) and supporting dimension tables, including dim_customers, dim_products, and dim_stores. Relationships between tables were established.
- Data Analysis: A date dimension table (dim_dates) was created, and key metrics were developed using DAX, including AOV, COGS, Profit, and Sales, along with Total Customers, Total Orders, and Total Stores. RFM Segmentation was also implemented.
- Data Visualization: An interactive dashboard was built in Microsoft Power BI with filters and slicers. KPIs, trends, and performance metrics were visualized.
