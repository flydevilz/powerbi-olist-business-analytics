# Olist Business Intelligence Dashboard

An end-to-end Business Intelligence solution developed using **Power BI**, **Python**, and **DAX** to analyze the Brazilian Olist e-commerce marketplace.

The project integrates transactional, marketing, and customer behavior datasets into a unified analytical platform, enabling executive-level decision making through interactive dashboards and KPI-driven insights.

---

# Project Overview

Modern e-commerce platforms generate massive amounts of operational, transactional, marketing, and customer data. However, these datasets are often fragmented across multiple systems, making it difficult for management to obtain a complete picture of business performance.

This project develops an integrated Business Intelligence solution for **Olist**, a Brazilian e-commerce marketplace, by combining multiple datasets into a centralized Power BI model.

The solution supports data-driven decision making across:

- Sales Performance
- Logistics & Delivery
- Seller Performance
- Marketing Funnel
- Customer Intelligence

---

# Business Objectives

The dashboard was designed around five business objectives:

- 📈 Sales & Revenue Analysis
- 🚚 Delivery Performance & Customer Satisfaction
- 🛍️ Seller Performance Evaluation
- 📢 Marketing Funnel Analysis
- 👥 Customer Segmentation (CLV & Churn Risk)

---

# Technologies

- Power BI
- DAX
- Power Query
- Python
- Pandas
- NumPy
- SQL
- Jupyter Notebook

---

# Datasets

The project integrates three datasets:

| Dataset | Description |
|----------|-------------|
| [Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) | Orders, customers, products, sellers, payments, reviews |
| [Olist Marketing Funnel Dataset](https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist)  | Lead generation and seller acquisition |
| [AI-generated Customer Behaviour](https://docs.google.com/spreadsheets/d/1JND5KOZNwIfsSw-gn-ZQDYB5dPfkHJTvjRtOLQNbaEI/edit?usp=drive_link) | Customer Lifetime Value (CLV), churn risk, engagement, purchasing behaviour |

---

# Project Workflow

```text
Raw Datasets
      │
      ▼
Python Data Cleaning
      │
      ▼
Power Query (ETL)
      │
      ▼
Galaxy Schema Data Model
      │
      ▼
DAX Measures & KPIs
      │
      ▼
Interactive Power BI Dashboards
```

---

# Data Model

The project uses a **Galaxy Schema (Fact Constellation Schema)** consisting of:

- 3 Fact Tables
- 13 Dimension Tables
- 5 Date Tables
- 16 Tables Total

The schema integrates:

- Orders
- Customers
- Sellers
- Marketing
- Products
- Reviews
- Payments
- Customer Behaviour

<img width="446" height="279" alt="image" src="https://github.com/user-attachments/assets/d36aff3e-c76a-4657-8c30-aa0577102009" />


---

# Dashboard Pages

## 🌐 Live Dashboard

View the interactive dashboard here:
👉 [Dashboard](https://app.powerbi.com/groups/me/reports/cfb34830-cfb2-4c89-ac92-af7aec2a1e1d?ctid=537c2be1-fcd4-45a9-83b3-6653eacc5070&pbi_source=linkShare)

## Executive Dashboard

**Focus**

- Revenue
- GMV
- Orders
- Product Categories
- Payment Methods
- YoY Growth

<img width="369" height="305" alt="image" src="https://github.com/user-attachments/assets/0e40b69c-d1b9-4842-9364-1e023a5494ab" />

---

## Operational Dashboard

**Focus**

- Seller Performance
- Marketing Funnel
- Seller Ranking
- Lead Conversion
- Revenue Distribution

<img width="351" height="282" alt="image" src="https://github.com/user-attachments/assets/a77d569b-e488-4c40-9a5c-67036e9ba15c" />

---

## Logistics Dashboard

**Focus**

- Delivery Performance
- On-time Delivery
- Customer Satisfaction
- Shipping Efficiency

<img width="345" height="277" alt="image" src="https://github.com/user-attachments/assets/3368d218-da31-4a89-beda-65dfa59d3fd5" />

---

## Customer Intelligence Dashboard

**Focus**

- Customer Lifetime Value
- Churn Risk
- Customer Segmentation
- Revenue Forecast
- Predictive Analytics

<img width="296" height="238" alt="image" src="https://github.com/user-attachments/assets/42feb905-517b-481d-88c7-78d4f58bcdaa" />

---

# Key Features

✅ Python ETL Pipeline

✅ Power Query Transformations

✅ Galaxy Schema Data Modelling

✅ Interactive Dashboards

✅ Drill-down Analysis

✅ DAX Measures

✅ KPI Cards

✅ Customer Segmentation

✅ Revenue Forecasting

---

# Example DAX Measures

Some business metrics developed include:

- Total GMV
- Total Orders
- Year-over-Year Growth
- YTD Revenue
- Customer Lifetime Value
- Churn Risk
- Late Delivery %
- Seller Ranking
- Average Review Score

---

# My Contributions

This was completed as a team project.

My primary contributions included:

- Data preprocessing using Python
- Data cleaning and feature engineering
- Power BI data modelling
- Galaxy Schema implementation
- DAX measure development
- Dashboard development
- Business analysis and report writing

---

# Repository Structure

```
dashboard/
    Olist_Dashboard.pbix

notebooks/
    data_cleaning.ipynb

reports/
    Business_Intelligence_Report.pdf
```

---

# Future Improvements

- Real-time dashboard refresh
- Azure SQL integration
- Power BI Service deployment
- Customer recommendation engine
- Sales forecasting using machine learning

