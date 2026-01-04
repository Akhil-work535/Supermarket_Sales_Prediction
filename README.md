# 🛒 Supermarket Sales Prediction

## 🔍 Business Problem
Supermarkets need data-driven sales forecasts to optimize inventory, staffing, and promotions.  
This project predicts **daily supermarket sales** using historical transaction data, store attributes, and promotional activity, helping improve planning and maximize revenue.

## 🎯 Objectives
- Understand key factors that influence sales
- Build regression models to **predict daily sales**
- Evaluate model performance using regression metrics
- Provide actionable insights supported by visualizations and dashboards

## 📊 Dataset Overview
- **Source:** Kaggle Supermarket Sales dataset  
- **Columns include:**
  - Invoice ID, Branch, City  
  - Customer Type, Gender  
  - Product Line, Unit Price, Quantity  
  - Tax, Total, Date, Payment, Rating
- **Size:** ~1000 rows with 14+ features :contentReference[oaicite:0]{index=0}

## 🧹 Data Preparation
- Converted `Date` to datetime object  
- Removed duplicates and handled missing values  
- Created derived features such as `Revenue` and `Total Tax`  
- Encoded categorical variables for modeling :contentReference[oaicite:1]{index=1}

## 🛠️ Modeling Approach
Regression models were trained to predict daily supermarket sales:

| Model | Primary Metric |
|-------|----------------|
| Linear Regression | Baseline |
| Random Forest Regressor | Improved |
| Gradient Boosting Regressor | Best Performance |

Evaluation used **RMSE, MAE, and R² score** to compare models and select the best one. :contentReference[oaicite:2]{index=2}

## 📈 Business Insights
- Branch performance varies significantly — some branches generate higher revenue but lower customer satisfaction. :contentReference[oaicite:3]{index=3}
- Promotions boost sales on weekends and holidays. :contentReference[oaicite:4]{index=4}
- Electronic payments are more common in urban branches. :contentReference[oaicite:5]{index=5}

These findings help retailers:
- Adjust inventory levels by predicted demand
- Tailor promotions by branch and customer type
- Allocate staff and resources based on expected footfall

## 📊 Visualization & Dashboard
Interactive **Power BI dashboard** includes:
- Actual vs. predicted sales plots  
- Branch-wise sales trends  
- KPI visuals for daily sales and revenue  
- Feature impact charts to support business decisions :contentReference[oaicite:6]{index=6}

## 🧰 Tools & Technologies
- **Python:** pandas, NumPy, scikit-learn  
- **Machine Learning:** Regression models  
- **Visualization:** Matplotlib, Seaborn, Power BI  
- **Notebook Environment:** Jupyter Notebook :contentReference[oaicite:7]{index=7}

## 🔑 Key Takeaways
- Regression models can reliably forecast supermarket daily sales  
- Feature engineering and promotion attributes significantly improve prediction quality  
- Dashboard visualization makes findings actionable for non-technical stakeholders

## 🚀 Future Enhancements
- Add external data such as holidays and weather to improve forecasts
- Evaluate more advanced models (XGBoost, LightGBM, Neural Networks)
- Deploy as a web API or Tableau/Power BI live dashboard

## 👤 Author
Akhil  
Aspiring Data Analyst / Data Scientist  
LinkedIn: http://www.linkedin.com/in/vankayalapati-akhil
