# 🛒 E-Commerce Customer Churn Analysis

A machine learning project focused on predicting and analyzing customer churn for an e-commerce platform. This notebook explores key factors that influence customer retention using data preprocessing, visualization, and classification model.

---

## 🎯 Project Overview

Customer churn is a critical issue for e-commerce platforms, as retaining customers is often more cost-effective than acquiring new ones. This project aims to:

* Understand patterns behind customer churn
* Identify important churn factors
* Develop a predictive model to classify churned customers

---

## 🗂️ Dataset

The dataset used in this project contains records of customer activity and engagement. Each row represents a customer with 20 features such as:

* **Demographic**: Gender, MaritalStatus, CityTier  
* **Engagement**: Tenure, PreferredLoginDevice, HourSpendOnApp  
* **Purchase Behavior**: PreferredPaymentMode, OrderAmountHikeFromlastYear  
* **Satisfaction**: SatisfactionScore, Complain  
* **Target**: Churn Indicator  

---

## ⚙️ Technologies Used

* **Python**
* **Pandas**, **NumPy** – data manipulation
* **Matplotlib**, **Seaborn**, **Plotly** – data visualization
* **Scikit-learn** – model building and evaluation
* **Colab Notebook** – analysis and documentation

---

## 📈 Workflow
This project follows the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology to systematically address the objective of customer churn prediction.

1. **Business Understanding**: Identified churn reduction as key goal.  
2. **Data Understanding**: Analyzed behavioral trends and churn signals.  
3. **Data Preparation**: Handled nulls, encoded categories, and scaled features.  
4. **Modeling**: Built/tuned XGBoost with hyperparameter optimization.  
5. **Deployment & Actionable Insights**: Delivered actionable retention strategies.  
   
---

## 📊 Performance Metrics

| Metric      | Score [before optimization] (%) | Score [after optimization] (%) |
|-------------|---------------------------------|--------------------------------|
| Accuracy    | 89                              | 92                             |
| Precision   | 62                              | 75                             |
| Recall      | 89                              | 82                             |
| F1-Score    | 73                              | 79                             |

---

## 📊 Key Results

### 🔝 Top 5 Churn Factors  
![Top Churn Factors](https://github.com/MeenakshiMony/E_Commerce_Customer_Churn_Analysis_Prediction/blob/main/Key_Churn_Factors.png)

Top 5 Features include:
1. Tenure  
2. CashbackAmount  
3. WarehouseToHome  
4. NumberOfAddress  
5. DaySinceLastOrder

### 📌 Customer Risk Segmentation  
![Risk Segmentation](https://github.com/MeenakshiMony/E_Commerce_Customer_Churn_Analysis_Prediction/blob/main/Risk_Segmentation.png)

**Actionable Insights**:  
- High-risk (Yellow): Target with personalized offers  
- Medium-risk (Orange): Improve engagement via app notifications  
- Low-risk (Blue): Maintain satisfaction through loyalty programs  

