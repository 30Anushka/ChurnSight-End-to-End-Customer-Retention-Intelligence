# 🧠 ChurnSight: End-to-End Customer Retention Intelligence (Power BI + SQL + ML)

**ChurnSight** is a complete end-to-end analytics and predictive modeling project designed to uncover the **drivers of customer churn** and support **data-driven retention strategies**.  
It integrates **SQL for data engineering**, **Python for machine learning**, and **Power BI for business intelligence**, forming a unified ecosystem for actionable customer insights.


## 🚀 Project Overview

Customer churn directly impacts profitability and long-term customer value.  
**ChurnSight** demonstrates how modern organizations can use data science and visualization tools to:
- Identify at-risk customers early  
- Predict churn likelihood using machine learning  
- Build retention dashboards for proactive decision-making  

This project replicates a real-world analytics lifecycle from **data extraction → predictive modeling → executive-level reporting**.

## 🧩 Project Workflow

### **1. Data Engineering (SQL)**
- Cleaned and joined multiple customer-related tables (Customer, Services, Contracts, Billing)
- Created derived fields for customer tenure, total charges, and churn flag
- Performed feature engineering to prepare the dataset for modeling

### **2. Exploratory Data Analysis (Python)**
- Conducted univariate and bivariate analysis to understand churn trends
- Visualized customer demographics, service usage, and contract behaviors
- Identified key churn indicators using correlation and feature importance metrics

### **3. Machine Learning Model (Python)**
- Preprocessed data using encoding, scaling, and feature selection
- Trained and tested multiple models:
  - Logistic Regression  
  - Random Forest  
  - XGBoost
- Generated churn probability scores for integration into Power BI

### **4. Business Intelligence (Power BI)**
- Built an interactive dashboard featuring:
  - **KPIs:** Churn %, Retention %, Avg Tenure  
  - **Trends:** Churn over time, region, contract type, and payment method  
  - **Drill-Downs:** Customer segment and revenue impact analysis  
- Provided actionable insights to support retention campaigns

## 💡 Key Insights

- **Month-to-month contract** customers churn the most due to low switching barriers.  
- **Fiber optic** users reported higher churn rates than DSL customers.  
- Customers using **electronic check payments** show higher churn likelihood.  
- Targeted retention offers for high-value customers can reduce churn by **15–20%**.

## ⚙️ Tech Stack

| Category | Tools / Technologies |
|-----------|----------------------|
| **Database** | SQL Server / MySQL |
| **Data Analysis** | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Machine Learning** | Scikit-learn, XGBoost, Python |
| **Visualization** | Power BI |
| **Environment** | Jupyter Notebook, Power BI Desktop |




