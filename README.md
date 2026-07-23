# Brazilian E-Commerce Intelligence Platform
## End-to-End Business Intelligence Project | Olist Dataset



# Overview

This project demonstrates the development of an end-to-end Business Intelligence solution using Excel, SQL, Python and Power BI.

The objective is to transform raw business data into actionable insights, supporting strategic decisions related to sales performance, customer behavior, logistics efficiency and operational improvements.

This project simulates the role of a BI Analyst working in a corporate environment, covering the entire data analytics lifecycle:

**Data Collection → ETL → Database → Analysis → Visualization → Business Recommendations**


---

# Business Problem

The company wants to better understand its e-commerce operation and identify opportunities to improve business performance.

The main objectives are:

- Understand sales performance and revenue drivers;
- Analyze customer behavior and purchasing patterns;
- Evaluate logistics efficiency and delivery performance;
- Identify high-performing products and categories;
- Generate strategic insights to support decision-making.

The final goal is to transform data into business intelligence.


---

# Business Questions

## Sales Performance

- What are the main revenue drivers?
- Which categories generate the highest revenue?
- How does sales performance evolve over time?
- Which regions contribute the most to business results?


## Customer Analytics

- Who are the most valuable customers?
- What is customer purchasing behavior?
- What factors influence customer satisfaction?
- Are customers returning to purchase again?


## Logistics Analysis

- What is the average delivery time?
- Which regions have the highest delivery delays?
- What factors impact customer experience?


## Product Analysis

- Which products generate the highest demand?
- Which categories have growth opportunities?
- Which products have low performance?


---

# Technologies

## Data Analysis & Visualization

- Excel
- Power BI


## Database

- SQL
- Relational Data Modeling


## Programming & Automation

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly


## Version Control

- Git
- GitHub


---

## 🔄 Project Workflow

```text
Data Collection
      │
      ▼
Data Cleaning & ETL (Python)
      │
      ▼
Database Modeling (SQL)
      │
      ▼
Exploratory Data Analysis (Excel)
      │
      ▼
Analytical Layer
      │
      ▼
Power BI Data Model
      │
      ▼
Dashboards
      │
      ▼
Storytelling
      │
      ▼
Business Recommendations
```

---

# Project Architecture

            Kaggle Dataset

                 ↓

          Python ETL Pipeline

                 ↓

          SQL Analytical Database

                 ↓

         Power BI Semantic Model

                 ↓

          Executive Dashboards

                 ↓

        Business Decision Support

  

---

## Repository Structure

```text
olist-bi-end-to-end/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
│
├── docs/
│   ├── Project_Plan.md
│   ├── Business_Understanding.md
│   ├── Data_Dictionary.md
│   ├── Architecture.md
│   ├── KPI_Definition.md
│   └── Storytelling.md
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── sql/
│   ├── create_database.sql
│   ├── create_tables.sql
│   ├── insert_data.sql
│   ├── views.sql
│   ├── procedures.sql
│   └── analytical_queries.sql
│
├── python/
│   ├── notebooks/
│   │   ├── 01_data_exploration.ipynb
│   │   ├── 02_data_cleaning.ipynb
│   │   ├── 03_feature_engineering.ipynb
│   │   └── 04_analysis.ipynb
│   ├── etl/
│   ├── eda/
│   ├── visualization/
│   └── utils/
│
├── excel/
│   ├── exploratory_analysis.xlsx
│   └── pivot_tables.xlsx
│
├── powerbi/
│   └── Olist_Dashboard.pbix
│
├── images/
│   ├── banner-github.png
│   ├── workflow.png
│   ├── architecture.png
│   ├── er_model.png
│   └── dashboard/
│       ├── executive.png
│       ├── sales.png
│       └── logistics.png
│
└── presentation/
    └── Executive_Presentation.pdf
```

---

# Dataset


## Source

**Brazilian E-Commerce Public Dataset by Olist**

Kaggle:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce


## Dataset Description

This dataset contains information about Brazilian e-commerce transactions, including:

- Customers
- Orders
- Products
- Categories
- Sellers
- Payments
- Reviews
- Delivery information
- Geographic data


The dataset allows the development of a complete Business Intelligence project, from data preparation to executive insights.


---

# Data Pipeline


## Step 1 - Data Collection

Raw data acquisition from Kaggle.


## Step 2 - Data Preparation

Using Python:

- Data cleaning;
- Missing value treatment;
- Data validation;
- Date standardization;
- Data transformation.


## Step 3 - Database Modeling

Using SQL:

- Table creation;
- Relationships;
- Data normalization;
- Analytical views.


## Step 4 - Data Analysis

Using Excel:

- Exploratory analysis;
- Pivot tables;
- Initial insights;
- Data validation.


## Step 5 - Business Intelligence

Using Power BI:

- Data modeling;
- DAX calculations;
- Interactive dashboards;
- Executive reports.


---

# Key Performance Indicators (KPIs)


## Sales KPIs

- Total Revenue
- Number of Orders
- Average Ticket
- Revenue Growth
- Sales by Category
- Sales by Region


## Customer KPIs

- Number of Customers
- Customer Retention
- Average Review Score
- Customer Segmentation


## Logistics KPIs

- Average Delivery Time
- Late Delivery Rate
- Freight Cost
- Delivery Performance


## Product KPIs

- Top Products
- Top Categories
- Product Performance
- ABC Analysis


---

# Expected Deliverables


The final project will include:


✅ Business Understanding Documentation


✅ Data Cleaning Pipeline with Python


✅ Structured SQL Database


✅ Analytical SQL Queries


✅ Exploratory Analysis using Excel


✅ Power BI Interactive Dashboards


✅ Executive Presentation


✅ Business Recommendations


---

# Project Status


| Stage | Status |
|-|-|
| Business Understanding | 🟢 Completed |
| Dataset Collection | 🟢 Completed |
| Data Preparation | ⚪ Pending |
| SQL Modeling | ⚪ Pending |
| Python ETL Pipeline | ⚪ Pending |
| Excel Analysis | ⚪ Pending |
| Power BI Dashboard | ⚪ Pending |
| Storytelling | ⚪ Pending |
| Final Presentation | ⚪ Pending |


---

# Final Objective


The purpose of this project is not only to create dashboards, but to demonstrate the ability to transform data into strategic decisions.

Through this solution, the project showcases the complete workflow expected from a Business Intelligence Analyst:

**Understand the business → Prepare the data → Analyze → Communicate insights → Support decisions.**
