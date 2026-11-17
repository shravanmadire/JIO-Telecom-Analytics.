# JIO-Telecom-Analytics.
The Jio Telecom Analytics Dashboard is a data analytics project developed using Microsoft Power BI. The main objective of this project is to analyse Jio's telecom business performance, customer behaviour, subscriber growth, revenue contribution, recharge plan performance and network quality.

The project uses telecom data from October 2021 to September 2026 to generate meaningful business insights through interactive dashboards and visualizations.
# 📊 Jio Telecom Analytics Dashboard – Power BI

## 📌 Project Overview

The **Jio Telecom Analytics Dashboard** is an end-to-end Business Intelligence project developed using Microsoft Power BI to analyze telecom business performance across customer segments, subscription plans, geographical circles, network usage, financial performance, and market competition.

The project transforms raw telecom datasets into meaningful business insights through data cleaning, data transformation, data modeling, DAX calculations, and interactive visualizations.

## 🎯 Project Objectives

- Analyze Jio's subscriber growth and customer performance.
- Evaluate prepaid and postpaid plan performance.
- Identify customer churn patterns and retention opportunities.
- Analyze regional and circle-wise telecom performance.
- Monitor 4G and 5G adoption and network coverage.
- Evaluate revenue, ARPU, EBITDA, and profitability trends.
- Compare Jio's market position with Airtel, Vodafone Idea, and BSNL.
- Identify business development and growth opportunities.

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Modeling
- Data Visualization

## 🗂️ Data Model

The project uses a **Fact Constellation (Galaxy) Schema** consisting of eight tables.

### Dimension Tables

| Table | Description |
|---|---|
| dim_date | Calendar and fiscal date information |
| dim_plan | Telecom recharge plan details |
| dim_circle | Geographical telecom circle information |
| customers_sample | Customer demographics, subscription and churn information |

### Fact Tables

| Table | Description |
|---|---|
| fact_plan_monthly | Monthly plan performance and revenue |
| fact_circle_monthly | Circle-wise subscriber and network performance |
| fact_national_monthly | National telecom and financial performance |
| fact_daily_usage | Daily/weekly data and voice usage observations |

## 📈 Key Analytical Areas

### 1. National Performance Analytics
- Subscriber growth trends
- Operating revenue and profitability
- ARPU analysis
- EBITDA and PAT
- National market share
- Competitor benchmarking

### 2. Customer Analytics
- Customer segmentation
- Active and churned customers
- Customer retention
- Churn reason analysis
- Customer spending patterns
- 4G and 5G customer distribution

### 3. Plan Analytics
- Prepaid vs Postpaid performance
- Plan-wise subscriber distribution
- Plan revenue contribution
- Average revenue per user
- Data consumption by plan
- 5G-eligible plan analysis

### 4. Circle Performance Analytics
- Circle-wise subscriber growth
- Regional revenue analysis
- Circle-wise ARPU
- Market share by telecom circle
- Subscriber rankings
- Churn analysis

### 5. Network Analytics
- 4G vs 5G subscriber distribution
- Network coverage
- Average download speed
- Network availability
- 5G adoption trends
- Fixed Wireless Access performance

### 6. Usage Analytics
- Data consumption trends
- Voice traffic analysis
- Prepaid vs Postpaid usage
- Weekday vs Weekend consumption
- Subscriber usage patterns

## 📊 Power BI Features Implemented

- Interactive dashboards
- DAX measures and calculated KPIs
- Power Query transformations
- Data modeling and relationships
- Drill-down and drill-through
- Interactive slicers and filters
- Report tooltips
- Bookmarks and navigation buttons
- Time-based analysis

## 💡 Business Outcomes

The analytical model supports business decision-making through:

- Identifying high-performing telecom circles.
- Understanding customer churn and retention opportunities.
- Recognizing high-performing subscription plans.
- Evaluating 4G and 5G expansion opportunities.
- Monitoring revenue and profitability trends.
- Understanding competitive market positioning.
- Identifying opportunities for customer acquisition and revenue growth.

## 📁 Project Files

| File | Description |
|---|---|
| JIO20.pbix | Power BI dashboard |
| Dataset files | Source telecom datasets |
| README.md | Project documentation |

## 👩‍💻 Author

**Data Analytics Project – Jio Telecom Analytics**

Skills demonstrated: Data Cleaning, Power Query, Data Modeling, DAX, Power BI, Business Intelligence, and Data Visualization.

---

⭐ If you find this project useful, consider giving this repository a star!
