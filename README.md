This version is designed with a clean, minimalist aesthetic using structured headers, bullet points, and professional formatting. It focuses on the "Action-Result" framework, which is what technical recruiters and hiring managers look for.

👨🏻‍💻Customer Behavior Data Analyst Portfolio Project

📌 Project Overview

This project provides a comprehensive analysis of customer purchasing behavior for a retail dataset. The objective was to transform raw transactional data into actionable business intelligence by identifying high-value customer segments, churn risks, and purchasing trends.

The core outcome: A data-driven strategy to optimize marketing ROI using RFM (Recency, Frequency, Monetary) modeling.

🛠️ Technical Toolkit

Data Processing: Python (Pandas, NumPy)

Database Management: SQL (CTEs, Window Functions, Aggregate Functions)

Exploratory Data Analysis (EDA): Matplotlib, Seaborn

Business Intelligence: Power BI (DAX, Power Query, Interactive Dashboards)

Environment: Jupyter Notebook, SQL Server / PostgreSQL

⚙️ Data Pipeline & Methodology
1. Data Extraction & Preprocessing (Python)

Cleaning: Addressed missing values, handled outliers using the IQR method, and standardized datetime objects.

Transformation: Merged multiple datasets (Sales, Customers, Products) to create a master analytical record.

Feature Engineering: Calculated individual customer lifetime value (CLV) and average transaction value.

2. Deep-Dive Analysis (SQL)

Segmentation: Developed RFM Analysis using SQL Window Functions (NTILE) to rank customers on a scale of 1–5.

Cohort Analysis: Wrote complex queries to track customer retention rates month-over-month.

Performance Metrics: Used Common Table Expressions (CTEs) to calculate "Year-over-Year" growth and "Top 10" performing product categories.

3. Business Intelligence Dashboard (Power BI)

DAX Modeling: Created custom measures for Active Customer Count, Churn Rate, and Revenue per Segment.

Visual Storytelling: Designed an interactive 3-page dashboard focusing on:

Executive Summary: High-level KPIs.

Customer Segmentation: RFM distribution map.

Product Insights: Identifying cross-selling opportunities.

📊 Key Insights & Results

High-Value Retention: 15% of the customer base (Champions) accounts for 52% of total revenue.

Churn Mitigation: Identified a 22% drop in repeat purchases in the "At-Risk" segment, leading to a recommendation for a win-back email campaign.

Seasonality: Peak purchasing occurs between 6:00 PM and 9:00 PM on weekdays, suggesting optimal times for ad spend.

Geographic Density: Top 3 cities contribute to 60% of the total order volume.

📁 Repository Structure
code
Text
download
content_copy
expand_less
├── 📂 Data                 # Raw and processed datasets
├── 📂 Notebooks            # Python scripts for cleaning and EDA
├── 📂 SQL_Queries          # Scripts for RFM scoring and business logic
├── 📂 Dashboard            # Power BI .pbix file and screenshots
└── README.md               # Project documentation

