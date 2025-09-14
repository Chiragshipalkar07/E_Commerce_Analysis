
# E-Commerce Sales Analysis

This project is an "E-Commerce Data Analysis" case study designed as part of a Data Analysis / Data Visualization course. The objective is to explore customer behavior, sales performance, profit distribution, and payment patterns using Power BI and Tableau dashboards.

## Project Overview
E-commerce platforms generate vast amounts of data related to customers, sellers, orders, payments, and delivery.
This project analyzes the dataset to uncover insights about:
• Total customers, sellers, sales, and profits
• Weekday vs. weekend payment behavior
• Sales trends across quarters
• Average shipping days vs. review scores
• Profitable states and payment types
• Product category–wise order distribution
• Customer city analysis based on price and payment value

Two interactive dashboards were created:
1. Power BI Dashboard – Multi-page analysis with KPIs, payment insights, review scores, and state/category analysis
2. Tableau Dashboard – Clean view of KPIs, customer spend, review vs. delivery insights, and payment method usage.
   
## Tools & Technologies
• Excel – Data preprocessing and cleaning.
• Power BI – Data modeling, DAX measures, KPI cards, slicers, and visual dashboards.
• Tableau – Visualization and storytelling dashboards.
• "Data Source – E-commerce dataset (Kaggle / provided course dataset).

## Power BI Dashboard
### Page 1
• KPIs: Total Unique Customers (30.56K), Total Sellers (1574), Total Sales (5M), Total Profit (975.35K).
• Weekday vs. Weekend Payment Stats (76.7% weekday, 23.3% weekend).
• Orders with Review Score = 5 by Payment Type (Credit Card, Boleto, Voucher).
• Average Shipping Days by Review Score (decreasing trend from \~18 to 11 days).
• Average Price vs. Average Payment Value by City (São Paulo shown).
• Quarterly Sales Trend (Q1: 0.5M → Q4: 2M).

### Page 2
• Top 5 Profitable States (SP: 448.09K highest, followed by MG, PR, SC, RJ)
• Average Review Score (4.15 out of 8.3)
• Orders Placed by Product Category Name (various product categories with counts)
• Total Profit by Payment Type (Credit Card 488.09K, Boleto 109.74K, others lower)
• Weekday/Weekend filter and Quarter filter for interactivity.

## Tableau Dashboard
• KPIs: "Total Customers (99,441), Total Profit (2.41M), Total Sales (16M), Total Sellers (3095)"
• Weekday vs. Weekend Payment Split (77.2% weekday, 22.8% weekend)
• Product Category – Pet Shop with average delivery days = 11
• Review Score vs. Delivery Days (higher scores linked to faster delivery)
• Customer City (São Paulo) – Avg. Payment Value = 135.04 vs. Avg. Price = 107.53
• Payment Method Usage – Credit Card most dominant
• Order counts by Product Category.

## Insights
• Most transactions occur on weekdays (around 77%).
• Credit card is the leading payment method, contributing the maximum profit.
• Higher review scores correlate with fewer shipping days".
• Quarter 4 shows peak sales (seasonal demand).
• A few product categories dominate orders, while others are niche.

## Future Improvements
• Add customer segmentation (RFM Analysis) for marketing insights
• Use forecasting models in Power BI for quarterly sales predictions
• Expand analysis with "geographical heatmaps" for city/state profits
• Perform sentiment analysis on reviews to link text with scores
• Automate data refresh pipelines for real-time reporting

## Learning Outcomes
• Built "multi-page Power BI dashboards" with KPIs, interactivity, and drilldowns
• Designed "Tableau dashboards" for simple comparative storytelling
• Learned how review scores, payment methods, and shipping days impact sales
• Gained experience in data cleaning, modeling, and visualization tools.
• Developed the ability to "derive business insights from raw e-commerce dataset.
