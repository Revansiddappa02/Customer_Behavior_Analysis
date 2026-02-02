# Customer Behavior Data Analyst Portfolio Project

<div align="center">

![Project Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## Overview

A comprehensive analysis of customer purchasing behavior for retail data, transforming raw transactions into actionable business intelligence. This project identifies high-value customer segments, churn risks, and purchasing trends through advanced analytics and visualization.

**Core Outcome:** Data-driven marketing strategy optimization using RFM (Recency, Frequency, Monetary) modeling.

---

## Tech Stack

<div align="center">

| Category | Technologies |
|----------|-------------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) |
| **Visualization** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Business Intelligence** | ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white) |
| **Environment** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) |

</div>

---

## Methodology

### Data Extraction & Preprocessing

**Cleaning**
- Addressed missing values and handled outliers using IQR method
- Standardized datetime objects for temporal analysis

**Transformation**
- Merged multiple datasets (Sales, Customers, Products) into master analytical record
- Feature engineering: Calculated customer lifetime value (CLV) and average transaction value

### Deep-Dive Analysis

**Segmentation**
- Developed RFM Analysis using SQL Window Functions (NTILE) for customer ranking (1-5 scale)

**Cohort Analysis**
- Tracked customer retention rates month-over-month using complex queries

**Performance Metrics**
- Leveraged CTEs for Year-over-Year growth and Top 10 product category analysis

### Business Intelligence Dashboard

**DAX Modeling**
- Created custom measures: Active Customer Count, Churn Rate, Revenue per Segment

**Visual Storytelling**
- Interactive 3-page dashboard covering:
  - Executive Summary (High-level KPIs)
  - Customer Segmentation (RFM distribution map)
  - Product Insights (Cross-selling opportunities)

---

## Key Insights

<table>
<tr>
<td width="50%">

**High-Value Retention**
- 15% of customer base (Champions) drives 52% of total revenue

**Churn Mitigation**
- 22% drop in repeat purchases among "At-Risk" segment
- Recommended win-back email campaign

</td>
<td width="50%">

**Seasonality**
- Peak purchasing: 6:00 PM - 9:00 PM on weekdays
- Optimal timing for ad spend allocation

**Geographic Density**
- Top 3 cities contribute 60% of total order volume

</td>
</tr>
</table>

---

## Repository Structure
```
.
├── data/                  # Raw and processed datasets
├── notebooks/             # Python scripts for cleaning and EDA
├── sql_queries/           # RFM scoring and business logic scripts
├── dashboard/             # Power BI .pbix file and screenshots
└── README.md             # Project documentation
```

---

## Getting Started

1. **Clone the repository**
```bash
   git clone https://github.com/yourusername/customer-behavior-analysis.git
```

2. **Install dependencies**
```bash
   pip install -r requirements.txt
```

3. **Explore notebooks**
```bash
   jupyter notebook
```

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with precision for data-driven decision making**

[Report Issues](https://github.com/yourusername/repo/issues) · [Request Feature](https://github.com/yourusername/repo/issues)

</div>

## Author [Revansiddappa](https://github.com/Revansiddappa02/)
