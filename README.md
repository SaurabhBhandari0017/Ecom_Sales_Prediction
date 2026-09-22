# 📊 Ecommerce Business Analysis
## 🚀 Project Overview
## This project analyzes an Ecommerce dataset using:
## EDA (Exploratory Data Analysis) → cleaning, summarizing, and visualizing data
## Dashboard (Power BI) → showing revenue, customers, categories, and countries
## Machine Learning (Linear Regression) → predicting transaction amounts
## SQL (Snowflake) → writing queries for analysis in an industry‑standard cloud data warehouse
## It’s a complete workflow: Data Cleaning - EDA → sql(Snowflake) → ML → Visuals.

# 📂 Steps Done
## 🔎 Exploratory Data Analysis (EDA)
## Cleaned data (duplicates, missing values)
## Checked distributions, correlations, and outliers
## Grouped by category, age, gender, country, payment mode
## Visualized with bar charts, pie charts, histograms, boxplots
## 👉 Found that quantity and unit_price strongly drive total_amt.

## SQL in Snowflake
## Industry‑convenient SQL queries were written in Snowflake to:
## Aggregate revenue by category, country, and payment mode
## Find top 5 countries by revenue
## Analyze customer distribution by age and gender
## Join tables for customer + order insights
## Use CTEs, window functions, and groupby queries for clean analysis
## 👉 Snowflake SQL is widely used in companies, so this adds real‑world relevance to the project.

## 🤖 Predictive Modeling
## Model: Linear Regression (scikit‑learn)
## Features: quantity, unit_price
## Target: total_amt
## Performance: R² = 0.79 → good accuracy for predictions

## 2. Dashboard Insights
## Total Revenue: $6M
## Top Category: Electronics ($2.7M)
## Top Countries: France, China, Australia, Brazil, Japan
## Top Payment Modes: COD & PayPal ($1.9M each)
## Balanced Customers: Gender and age groups almost equal

## 📌 Recommendations
## Boost Electronics but grow Home & Kitchen/Apparel
## Improve customer ratings with better service
## Strengthen COD & PayPal infrastructure
## Expand in France, China, Australia
## Use regression model for pricing & revenue forecasting
## Keep using Snowflake SQL for scalable, industry‑ready analysis
