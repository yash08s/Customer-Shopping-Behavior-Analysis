# Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior for a retail business using **Python, SQL, and Power BI**. The analysis focuses on understanding what customers buy, how they shop, and which factors such as discounts, reviews, payment methods, and demographics are associated with purchasing behavior.

The goal is to turn the raw customer data into useful insights that can help improve sales, customer engagement, and retention.

## Overview

- **Dataset:** Customer shopping behavior data
- **Tools Used:**
  - Python
  - SQL
  - Power BI
  - Jupyter Notebook
- **Skills Applied:**
  - Data Cleaning & Preprocessing
  - Exploratory Data Analysis
  - SQL Analysis
  - Customer Segmentation
  - Data Visualization
  - Business Analysis

## Dataset

The dataset contains customer-level shopping information such as:

- Customer demographics
- Product categories
- Purchase amounts
- Discounts
- Review ratings
- Payment methods
- Purchase frequency
- Shopping preferences

The raw dataset is included in the repository:

- [Customer Shopping Behavior Dataset](./data/customer_shopping_behavior.csv)

## Python Analysis

Python was used to clean and prepare the dataset before performing the SQL analysis.

The notebook covers:

- Loading and exploring the dataset
- Checking missing and duplicate values
- Cleaning and transforming columns
- Understanding customer and product patterns
- Exploratory data analysis
- Preparing the final dataset for SQL

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

Notebook:

[Customer Behavior Analysis](./notebooks/customer_behavior_analysis.ipynb)

## SQL Analysis

After cleaning the data, the dataset was loaded into a SQL database to answer different business questions.

Some of the analysis includes:

| Business Question | Analysis |
|---|---|
| Customer distribution | Customers by age group and demographic |
| Product performance | Purchases across different product categories |
| Spending behavior | Average and total purchase amount |
| Discount analysis | Purchase behavior of customers using discounts |
| Review analysis | Relationship between ratings and purchasing behavior |
| Payment preferences | Most commonly used payment methods |
| Purchase frequency | Customers with higher purchase frequency |
| Customer segmentation | Comparing different customer groups |
| Repeat purchases | Identifying patterns in customer loyalty |

SQL queries used for the analysis:

[SQL Queries](./sql/customer_behavior_analysis.sql)

## Power BI Dashboard

The cleaned data and SQL analysis were used to create an interactive Power BI dashboard.

The dashboard includes:

- Customer overview
- Purchase and sales metrics
- Product category analysis
- Customer demographics
- Discount usage
- Payment method preferences
- Review ratings
- Purchase frequency
- Customer segmentation

Power BI file:

[Customer Behavior Dashboard](./powerbi/customer_behavior_dashboard.pbix)

## Key Insights

The analysis is used to identify patterns such as:

- Which customer groups purchase more frequently
- Which product categories are most popular
- How discounts influence purchasing behavior
- Which payment methods customers prefer
- Differences in shopping behavior across demographics
- Patterns associated with repeat purchases and customer loyalty

The detailed findings are available through the SQL analysis and Power BI dashboard.

## Project Structure

```text
Customer-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
└── README.md
