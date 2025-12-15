# **Supermarket Sales Analysis**

## Executive Summary


This project focuses on predicting daily sales for a supermarket using historical sales data, store information, and promotional activities. By leveraging machine learning models and Power BI dashboards, it identifies key factors influencing sales, helping optimize inventory, plan promotions effectively, and maximize revenue.

## Business Problem


Supermarkets face challenges in managing inventory, planning promotions, and improving profitability. Management wants to understand:

* Customer purchasing behavior
* Product performance
* Payment trends

**Goal:** Analyze transactional data to extract actionable insights and recommend strategies for revenue improvement.

## Methodology



1. Data Cleaning & Preparation: Handle missing and duplicate entries, convert date columns, create derived columns like `Revenue` and `Total Tax`.
2. Feature Engineering: Encode categorical variables and create promotion-related features.
3. Exploratory Data Analysis (EDA): Identify sales trends, seasonality, and branch-wise performance.
4. Model Training: Apply regression models (Random Forest, Linear Regression, Gradient Boosting) for sales prediction.
5. Evaluation: Measure performance using RMSE, MAE, and R² score.
6. Visualization: Build interactive dashboards in Power BI for actionable insights.

## Dataset



* **Source:** [Kaggle Supermarket Sales Dataset](https://www.kaggle.com/datasets/username/datasetname)
* **Contents:** Invoice ID, Branch, City, Customer Type, Gender, Product Line, Unit Price, Quantity, Tax, Total, Date, Payment, Rating
* **Size:** 1000+ rows, 14 columns

## Skills



* Data Analysis & Manipulation: Python, Pandas, NumPy
* Visualization: Matplotlib, Seaborn, Power BI
* Machine Learning: Regression models (Random Forest, Linear Regression, Gradient Boosting)
* Data Storytelling: KPI dashboards, interactive reports, business insights

## Results & Business Recommendations



* Branch B generates the highest revenue but lower customer satisfaction.
* Electronic payments dominate urban branches.
* High-performing product lines include [insert top products].
* Promotional campaigns significantly increase sales during weekends.

**Recommendations:**

* Plan promotions strategically for low-performing branches.
* Adjust inventory based on predicted daily sales trends.
* Monitor high-performing stores to replicate best practices.

## Next Steps



* Integrate external data such as holidays and weather for improved predictions.
* Explore advanced ML models like XGBoost or LSTM for better forecasting.
* Automate Power BI dashboards with live data for real-time decision-making.
* Optimize inventory and promotional strategies using model insights.
