# IKEA Gifting – Customer Analytics & RFM Segmentation

**End-to-End Data Analytics Project using SQL, Python & Power BI**

**Author:** Ishika Pathak

## Project Overview

This project focuses on analyzing customer purchasing behaviour for a fictional UK-based e-commerce gifting and home décor business, IKEA Gifting.

The objective is to identify valuable customers, understand purchasing patterns, analyze customer retention, and identify customers at risk of churning.

The project follows an end-to-end analytics workflow using SQL for data cleaning, Python for RFM analysis and customer segmentation, and Power BI for interactive dashboard development.

*Note: IKEA Gifting is a fictional business created for this portfolio project and is not affiliated with the actual IKEA corporation.*

## Business Objectives

- Identify high-value customers and their revenue contribution.
- Analyze customer purchasing behaviour and retention.
- Identify customers at risk of churning.
- Understand revenue trends across different periods and countries.
- Develop actionable customer retention strategies.

## Dataset

**Source:** [Online Retail II – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

- Time Period: December 2009 – December 2011
- Total Records: 1,067,371
- Dataset Format: Excel (Two sheets)
- Domain: E-commerce / Retail

## Tools & Technologies

| Tool | Purpose |
|---|---|
| SQL Server | Data cleaning, transformation and exploration |
| Python (Pandas, NumPy) | RFM analysis and customer segmentation |
| Jupyter Notebook | Python analysis |
| Power BI | Interactive dashboards and visualization |
| DAX | KPI calculations and measures |

## Project Workflow

**1. Data Cleaning & Exploration – SQL**
- Imported and combined both dataset sheets.
- Handled inconsistent date formats and data types.
- Identified and removed 32,907 duplicate records.
- Performed data validation and exploratory queries.

**2. RFM Analysis – Python**

Calculated Recency, Frequency, and Monetary values to understand customer purchasing behaviour.

Customers were scored and classified into six segments:
- Champions
- Loyal
- At Risk
- New
- Needs Attention
- Lost

Also implemented a 90-day inactivity threshold to identify churned customers.

**3. Dashboard Development – Power BI**

Developed a two-page interactive dashboard:

- **Page 1 – Business Overview:** Total customers, revenue, churn percentage, average customer value, customer distribution, and revenue trends.
- **Page 2 – RFM Analysis:** Customer segment performance, revenue contribution, average RFM scores, customer value, and churn trends.

Added interactive filters for month, quarter, year, country, customer segment, and churn status.

## Key Insights

- Champions represent approximately 22% of customers and contribute close to 68% of total revenue.
- Overall customer churn is approximately 50.86%, based on a 90-day inactivity threshold.
- Customer value varies significantly across different segments.
- Revenue shows noticeable seasonal growth during Q4.

## Business Recommendations

- Reward Champions through loyalty programs and exclusive offers.
- Encourage repeat purchases from Loyal customers.
- Target At Risk customers through personalized re-engagement campaigns.
- Improve onboarding and engagement for New customers.
- Develop win-back strategies for Lost customers.

## Project Structure

```text
IKEA-Gifting-Customer-Analytics/
│
├── SQL/
├── Python/
├── PowerBI/
├── Dashboard_Screenshots/
└── README.md
```

## Key Skills Demonstrated

SQL | Python | Pandas | Data Cleaning | EDA | RFM Analysis | Customer Segmentation | Churn Analysis | Power BI | DAX | Business Intelligence | Data Visualization


