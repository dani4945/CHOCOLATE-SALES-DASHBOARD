# CHOCOLATE-SALES-DASHBOARD

1.🍫 Sweet Insights: Chocolate Sales Performance Dashboard
A dynamic, interactive data visualization tool built to explore chocolate sales data across 6 global markets — focusing on product performance, salesperson rankings, regional revenue distribution, and year-over-year shipment trends.

2.Description
The Sweet Insights Dashboard is a visually engaging and analytical Power BI report designed to help stakeholders explore and analyze over 25,076 shipment records covering $141M in revenue and 9M boxes shipped across 6 countries. The dashboard focuses on highlighting key metrics like CY vs PY sales trends, profit margins, top-performing products, salesperson leaderboards, and geo-based revenue distribution — intended for use by retail sales managers, regional heads, and business analysts who need clear visibility into chocolate sales operations.

3. Tech Stack
The dashboard was built using the following tools and technologies:
🖥️ Power BI Desktop – Main data visualization platform used for report creation
🔄 Power Query – Data transformation and cleaning layer for reshaping and preparing the data
📊 DAX (Data Analysis Expressions) – Used for calculated measures, CY vs PY comparisons, profit %, KPI cards, and dynamic ranking logic
🔗 Data Modeling – Star schema relationships established across 5 tables (sales, products, salesperson, geography, calendar) to enable cross-filtering and aggregation
📁 File Format – .pbix for development and .png for dashboard previews

4.Data Source
Source: Kaggle – Chocolate Sales Dataset
The dataset was sourced from Kaggle as an Excel file (.xlsx) containing 25,076+ shipment records across multiple sheets. It was loaded into Power BI via Power Query where it was cleaned, reshaped, and modeled into a structured star schema.
The dataset includes the following key fields:

Product Details – Product name, category
Sales Info – Sale amount, boxes shipped, profit, profit %, shipment count
Salesperson Info – Salesperson name, profile picture, individual performance metrics
Geography – Country (India, Australia, New Zealand, USA, UK, Canada)
Date – Calendar date for CY vs PY time intelligence analysis (Jan 2023 – Mar 2025)

5. Features / Highlights
5.1 Business Problem

Retail sales teams and category managers lacked a unified view of chocolate product performance, salesperson contributions, and regional sales trends — making it difficult to identify profit decline patterns, rank top performers, and compare current year results against the previous year in real time.

5.2 Goal of the Dashboard

To build a comprehensive, filterable sales analytics dashboard that enables teams to monitor $141M in revenue, track 57.32% overall profit margin, compare CY vs PY trends, rank top products and salespersons, and analyze geo-level distribution — all within a single Power BI report.

5.3 Key Visuals Used 

The dashboard features 5 KPI cards at the top (Total Amount $141M, Total Boxes 9M, Total Profit $81M, Profit % 57.32%, Shipment Count 25K) with a global date slicer. The CY vs PY line charts track monthly revenue and box volume against the prior year. A shipment count histogram shows distribution across box quantity ranges. The Amount by Geo donut chart breaks down revenue across 6 countries with India leading at $40M (28.56%). The Top 6 Salesperson leaderboard ranks representatives by amount, boxes, and profit % with profile photos. The Top 6 Products bar highlights best sellers, while the Our Products table shows all products ranked by profit %.

5.4 Business Impact & Insights

Total revenue reached $141M across 25K+ shipments covering 9M boxes globally
Overall profit margin stands at 57.32% — with Peanut Butter Cubes leading at 90.24% profit, the highest among all products
India dominates revenue at $40M (28.56%), followed by Australia at $30M (21.09%) and New Zealand at $30M (21.27%)
Canada underperforms at just $10M (7.07%) despite being a key market — indicating a potential sales coverage gap rather than a demand issue
Ponnan leads the salesperson leaderboard with $11.7M in sales and 724.9K boxes at 58.85% profit
CY vs PY trend lines reveal a visible dip in early 2025, signaling a need for strategic intervention in Q1 performance

6.Snapshot Of My Dashboard
[Dashboard Preview (Chocolate Sales Report)](https://github.com/dani4945/CAR-SALES-DASHBOARD/blob/main/Snapshot%20of%20Car%20Sales%20Dashboard%20Details%20Report.png)
