# Credit Score Analysis and Prediction

## 📖 Project Overview
This project focuses on analyzing customer financial data and predicting credit scores using machine learning.  
It explores how income, spending habits, employment type, credit utilization, and late payments influence a customer's credit score.

The project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Machine Learning model training
- Model evaluation and interpretation

---

## 📊 Exploratory Data Analysis (EDA)

### Credit Score Distribution
![Credit Score Distribution](images/credit_score_distribution.png)

### Average Credit Score by Employment Type
![Employment vs Credit Score](images/employment_vs_credit.png)

### Credit Utilization Rate vs Credit Score
![Credit Utilization vs Credit Score](images/credit_utilization_scatter.png)

### Credit Score by Education Level
![Education vs Credit Score](images/education_vs_credit.png)

### Correlation Matrix
![Correlation Heatmap](images/correlation_heatmap.png)

**Insights:**
- Most credit scores are between 400–500
- Full-time and retired individuals have higher credit scores
- Credit utilization and late payments negatively impact scores
- Higher education levels slightly improve credit scores

---

## 🤖 Machine Learning Model

- Model used: **Random Forest Regressor**
- Features scaled using **StandardScaler**
- Employment type encoded using one-hot encoding

### Model Performance

#### Actual vs Predicted Credit Scores
![Actual vs Predicted](images/actual_vs_predicted.png)

#### Feature Importance
![Feature Importance](images/feature_importance.png)

**Key Points:**
- Strong predictive performance
- Predictions mostly fall near the actual values
- Credit utilization, late payments, and annual income are the most important features
