# Customer Churn Prediction

## Project Overview

Customer churn prediction is a machine learning project aimed at identifying customers who are likely to leave a company. Retaining existing customers is often more cost-effective than acquiring new ones, making churn prediction an important business application.

This project uses a banking customer dataset to analyze customer behavior and build classification models capable of predicting whether a customer will leave the bank or continue using its services.

---

## Problem Statement

Customer churn occurs when a customer stops using a company's products or services. The objective of this project is to build a predictive model that can classify customers into:

* **Exited (1)** – Customer has left the bank.
* **Not Exited (0)** – Customer continues to use the bank's services.

The insights generated from this model can help organizations develop customer retention strategies and reduce churn rates.

---

## Dataset Information

The dataset contains customer information collected from a banking institution.

### Features

| Feature         | Description                             |
| --------------- | --------------------------------------- |
| CreditScore     | Customer credit score                   |
| Geography       | Customer's country                      |
| Gender          | Customer gender                         |
| Age             | Customer age                            |
| Tenure          | Number of years with the bank           |
| Balance         | Account balance                         |
| NumOfProducts   | Number of bank products used            |
| HasCrCard       | Whether the customer owns a credit card |
| IsActiveMember  | Customer activity status                |
| EstimatedSalary | Estimated annual salary                 |
| Exited          | Target variable indicating churn        |

### Target Variable

* 0 → Customer stays
* 1 → Customer leaves

---

## Project Workflow

### 1. Data Understanding

* Explore dataset structure
* Analyze feature types
* Check for missing values and duplicates

### 2. Exploratory Data Analysis (EDA)

* Analyze customer demographics
* Study churn distribution
* Identify relationships between features and churn

### 3. Data Preprocessing

* Remove unnecessary columns
* Encode categorical features
* Scale numerical features
* Split data into training and testing sets

### 4. Model Development

The following machine learning algorithms will be evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest

Additional models may be explored during project development.

### 5. Model Evaluation

Models will be evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

### 6. Feature Importance Analysis

Feature importance techniques will be used to identify the factors that contribute most to customer churn.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Expected Outcomes

* Identify customers with a high probability of churn.
* Understand key factors influencing customer retention.
* Compare multiple machine learning algorithms.
* Generate actionable business insights from customer data.

---

## Future Enhancements

* Hyperparameter tuning
* Advanced ensemble models
* Interactive dashboard
* Web application deployment
* Real-time churn prediction system

---

## Project Status

🚧 Work in Progress

The project is currently under development. Exploratory Data Analysis, model training, evaluation, and deployment phases are ongoing and will be updated as the project progresses.
