# 🛒 E-Commerce Customer Churn Analysis

A machine learning project focused on predicting and analyzing customer churn for an e-commerce platform. This notebook explores key factors that influence customer retention using data preprocessing, visualization, and classification model.

---

## 📌 Project Overview

Customer churn is a critical issue for e-commerce platforms, as retaining customers is often more cost-effective than acquiring new ones. This project aims to:

* Understand patterns behind customer churn
* Identify important churn factors
* Develop a predictive model to classify churned customers

---

## 📊 Dataset

The dataset used in this project contains records of customer activity and engagement. Each row represents a customer with 20 features such as:

* Demographic - Gender, maritalStatus, CityTier
* Service Usage & Engagement - Tenure, PreferredLoginDevice, HourSpendOnApp, etc
* Purchase Behaviour & Financial - PreferredPaymentMode, OrderAmountHikeFromlastYear, OrderCount, etc
* Customer Satisfaction & Support - SatisfactionScore, Complain 
* Churn Indicator (target variable)

---

## ⚙️ Technologies Used

* **Python**
* **Pandas**, **NumPy** – data manipulation
* **Matplotlib**, **Seaborn** – data visualization
* **Scikit-learn** – model building and evaluation
* **Jupyter Notebook** – analysis and documentation

---

## 📈 Workflow
This project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology to systematically address the objective of customer churn prediction.

1. **Business Understanding** - Clarified the objective to proactively reduce churn through predictive insights tailored for e-commerce dynamics.
2. **Data Understanding** - Investigated customer lifecycle data to uncover usage trends and behavioral signals indicative of churn risk.
3. **Data Preparation** - Refined the dataset by imputing nulls, encoding categories, and scaling features to ensure modeling readiness.
4. **Modeling** - Implemented XGBoost, classification model to predict churn factors. Tuned hyperparameters using sklearn.metrics for better accuracy.
5. **Deployment & Actionable Insights** - Identified key churn drivers such tenure and cashback amount, and recommended data-driven retention strategies accordingly.
   
---

## 📌 Key Results

* Identified top churn factors, such as tenure, CashbackAmount, WarehouseToHome, DaySinceLastOrder, Complaint
* Achieved high accuracy of 92% by hypperparameter tuning on XGBoost using sklearn.metrics
* Segmented customers as high, medium and low risk and recommend actionable insights that could help e-commerce companies reduce churn

