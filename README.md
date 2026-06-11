# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn is one of the most important challenges faced by subscription-based businesses. Customer churn occurs when a customer stops using a company's products or services. Predicting churn helps organizations take proactive measures to retain valuable customers.

This project uses Machine Learning techniques to analyze customer behavior and predict whether a customer is likely to churn.

---

## Objective

The main objective of this project is to:

* Understand customer behavior patterns
* Identify factors contributing to customer churn
* Perform Exploratory Data Analysis (EDA)
* Build a machine learning model to predict churn
* Generate actionable business insights

---

## Dataset Description

The dataset contains customer demographic information, account details, subscription information, and billing records.

### Features

* customerID
* gender
* SeniorCitizen
* Partner
* Dependents
* tenure
* PhoneService
* InternetService
* Contract
* PaymentMethod
* MonthlyCharges
* TotalCharges

### Target Variable

* Churn

  * Yes = Customer leaves the service
  * No = Customer stays with the service

---

## Tasks Performed

### Task 1: Dataset Understanding

* Loaded dataset using Pandas
* Explored dataset structure
* Identified data types
* Examined dataset dimensions
* Understood feature descriptions


### Task 3: Exploratory Data Analysis (EDA)

* Generated descriptive statistics
* Analyzed customer churn patterns
* Studied relationships between features
* Investigated tenure, contract type, and monthly charges
* Identified key factors affecting churn

### Task 5: Predictive Modeling

Machine Learning model used:

* Random Forest Classifier

Model workflow:

1. Train-test split
2. Model training
3. Prediction generation
4. Performance evaluation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Model Performance

### Accuracy

80%

### Classification Report

* Precision (Churn): 68%
* Recall (Churn): 47%
* F1-Score (Churn): 56%

The model performs well in identifying non-churning customers and provides a reasonable baseline for churn prediction.

---

## Key Findings

* Customers with shorter tenure are more likely to churn.
* Higher monthly charges are associated with increased churn probability.
* Long-term contract customers are less likely to leave the service.

---

## Business Impact

Customer churn prediction enables companies to:

* Improve customer retention
* Reduce revenue loss
* Identify at-risk customers early
* Develop targeted retention strategies
* Improve overall customer satisfaction

---

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Class imbalance handling using SMOTE
* XGBoost implementation
* Model deployment using Streamlit
* Real-time churn prediction system

---

## Conclusion

This project demonstrates the complete machine learning workflow, from data understanding and preprocessing to model building and evaluation. The developed model successfully predicts customer churn and provides valuable insights that can help businesses improve customer retention and decision-making.
