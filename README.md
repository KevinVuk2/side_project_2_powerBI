<img width="1415" height="838" alt="{CD0CB487-5822-42FB-9656-662D03F1E180}" src="https://github.com/user-attachments/assets/3749fb11-620d-4547-95a2-b5d595a3bbfd" />

# 🛍️ Fashion Store E-commerce Dashboard

This repository contains the Power BI project file and datasets for a comprehensive analytics solution built for an online fashion retailer. The dashboard uncovers deep insights into customer behavior, product performance, sales trends, campaigns, and operational efficiency.

# Table of Contents

1. Project Overview
2. Key Insights
3. Dashboard Visualizations
4. Technical Details

# 🚀 Project Overview

This project analyzes multi-channel e-commerce sales data using an interactive Power BI dashboard.
It leverages sales, products, customers, campaigns, and inventory data to answer critical business questions such as:

- Which products drive the most revenue?
- How do marketing campaigns affect sales?
- What is the customer ordering pattern over time?
- Which channels perform the best?
- What stock issues require attention?

The focus is to provide a full end-to-end analytics view of the fashion store’s performance for strategic decision-making.

💡 Key Insights

Here are some of the metrics and findings surfaced in the dashboard:
1. Sales & Orders
- Order frequency reveals clear weekly and monthly seasonality, with peaks driven by campaigns and channel pushes.
- A dynamic moving average line helps track performance trends over time.
- Top-performing months contribute disproportionately to overall revenue.
2. Product Performance
- The Top 5 best-selling products generate a significant percentage of total sales.
- A separate analysis highlights bottom 5 products, useful for stock clearance, discontinuation, or marketing improvement.
3. Customer Insights
- Customer base spans multiple countries and age groups.
- Repeat purchases and order patterns help understand customer loyalty.
4. Marketing Campaign Impact
- Campaign-linked sales correlate strongly with promotional windows.
- WoW (week-over-week) and MoM (month-over-month) metrics evaluate campaign success.
- KPIs include arrows showing performance shifts over time.
5. Channel Overview
- Sales channels (e.g., Online, Retail, Mobile App) show distinct performance and customer engagement patterns.

# 📊 Dashboard Visualizations

The Power BI dashboard includes:
1. Sales Overview
- Total Sales, Orders, AOV (Average Order Value)
- Weekly & Monthly Sales Trends
- Moving Average Trend Line
- WoW & MoM KPIs with directional arrows

2. Product Analytics
- Top 5 Best & Worst Product Sellers
- Product Category Performance
- Profitability (if cost data provided)
- Inventory Levels vs Sales Velocity

3. Customer Profile
- Customer Demographics (Age Range, Country)
- Customer Lifetime Metrics
- Order Frequency & Recency Patterns

4. Marketing & Campaign Tracking
- Sales uplift during campaign date ranges
- Campaign-to-Sales mapping via DAX logic
- Channel-specific performance
- Campaign ROI potential

5. Channel Performance
- Revenue by sales channel
- Orders by channel
- Customer share per channel

🛠️ Technical Details

- Tools: Power BI Desktop – Data modeling, DAX calculations, dashboard creation, Excel / CSV – Raw data processing
- Data Model: A star-schema structure connecting fact tables such as: Sales, SalesItems, Stock
- Key DAX Features: Moving Averages, Week-over-Week (WoW) comparisons, Campaign ID mapping based on date ranges, Top N (Top 5 / Bottom 5) ranking & table generation, Linear baseline metrics (e.g., average orders per week/month)
- Data Source: The visualizations are based on datasets from Kaggle.
