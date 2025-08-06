# 📊 Customer Churn Prediction and Analysis

## 🧠 Overview
This project explores customer churn behavior in a subscription-based telecom business. By leveraging data science and machine learning techniques, the goal is to **predict churn**, uncover **insights from customer behavior**, and provide **strategic recommendations** for churn reduction.

---

## 📌 Problem Statement
Customer churn is a critical issue for subscription-based businesses. Retaining customers is more cost-effective than acquiring new ones. Hence, predicting which customers are likely to churn enables businesses to take proactive steps for retention.

---

## 🎯 Objectives
- Analyze customer churn rates and identify high-risk groups.
- Visualize patterns in churn based on demographics and service usage.
- Build and evaluate multiple machine learning models for churn prediction.
- Provide actionable business insights to reduce churn.

---

## 🗂️ Dataset
- **Source**: Telco Customer Churn dataset (CSV format)
- **Attributes**: Demographics, account details, service subscriptions, charges, and churn status.
- **Target Variable**: `Churn` (Yes/No)

---

## 🛠️ Tools & Libraries Used
- **Languages**: Python
- **Libraries**: 
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn`, `plotly` – Visualization
  - `sklearn`, `xgboost`, `catboost` – Machine learning models
  - `missingno` – Handling missing data

---

## 🔍 Exploratory Data Analysis (EDA)
**Key Insights:**
- Customers with **month-to-month contracts** had the highest churn.
- Those using **electronic checks** as payment showed greater churn.
- **Fiber optic** users had higher churn than DSL users.
- **Lack of online security and tech support** strongly correlates with higher churn.
- **New users (low tenure)** and those with **high monthly charges** are more likely to churn.

---

## 🧹 Data Preprocessing
- Dropped unnecessary columns like `customerID`
- Converted `SeniorCitizen` numeric to categorical
- Handled missing values in `TotalCharges`
- One-hot encoding for categorical features
- Feature scaling using `StandardScaler`
- Train-test split for model training

---

## 🤖 Machine Learning Models & Accuracy

| Model                    | Accuracy      |
|--------------------------|---------------|
| K-Nearest Neighbors      | 71.69%        |
| Support Vector Machine   | 73.45%        |
| Logistic Regression      | 79.08%        |
| Decision Tree Classifier | 72.36%        |
| AdaBoost Classifier      | 79.27%        |
| Gradient Boosting        | 79.69%        |
| **Random Forest**        | **80.02%** ✅ |

---

## 📈 Model Evaluation
- **Confusion Matrix**
- **ROC-AUC Curve**
- **Precision, Recall, F1-Score**

**Random Forest** model showed the best performance across metrics and was selected as the final model.

---

## 📊 Business Recommendations
- Encourage long-term contracts to reduce churn.
- Improve service quality for **fiber optic** customers.
- Offer discounts or incentives to **new customers**.
- Target users with **electronic check** payment for personalized engagement.
- Promote **tech support and online security** packages.

---

## 📁 Project Structure
