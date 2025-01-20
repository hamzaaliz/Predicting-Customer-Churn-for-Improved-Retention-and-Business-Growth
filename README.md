# Predicting Customer Churn for Improved Retention and Business-Growth

## Project Overview

The **Customer Churn Prediction** project aims to predict customer churn for a business using machine learning models. By leveraging data from customer features, such as credit score, age, balance, and product ownership, the goal is to accurately predict which customers are at risk of leaving. The business can then take proactive steps to reduce churn and improve customer retention.

### **Business Goals**
- **Predict customer churn with high accuracy**: Identify customers at risk of churning to take proactive retention actions.
- **Increase retention rates**: By targeting customers at risk, the goal is to reduce churn and improve customer lifetime value.
- **Enhance user engagement**: Proactively engaging customers identified as at risk with retention strategies.

## Problem Statement

To meet the business goals, the problem we are addressing is:
- **Predict which customers are at risk of churning**
- **Achieve an accuracy of at least 80% in predicting customer churn**

## Approach

### **Data Analysis**
- Analyze key features that impact customer churn such as **credit score**, **age**, **balance**, and **product ownership**.
- Identify patterns and correlations that may indicate a higher likelihood of churn.

### **Model Development**
- Build and compare three different predictive models:
  1. **Logistic Regression**
  2. **Random Forest**
  3. **XGBoost**

### **Model Evaluation**
- Use metrics such as **Recall** and **Accuracy** to evaluate model performance.
  - **Recall** ensures that at-risk customers are correctly identified.
  - **Accuracy** ensures the model performs well across both churned and non-churned customers.

## Model Development

### **Data Preprocessing**
- **Standardized** numeric features (e.g., credit score, balance, age).
- **Encoded** categorical features (e.g., gender, country, product ownership) using **Label Encoding**.
  
### **Models Created:**
1. **Logistic Regression**
2. **Random Forest**
3. **XGBoost**

### **Evaluation Metrics:**
- **Recall**: Measures how many of the at-risk customers are correctly identified.
- **Accuracy**: Measures the overall prediction quality of the model.

## Results

- **XGBoost** performed the best with a **Recall of 0.52** and an **Accuracy of 0.87**.
- **Random Forest** was fine-tuned and achieved a **Recall of 0.45** and **Accuracy of 0.86**.
- **Logistic Regression** performed poorly with a **Recall of 0.15** and **Accuracy of 0.81**.
  
Based on these results, **XGBoost** was chosen as the final model for predicting customer churn.

## Recommendations

- Offer **credit score improvement programs** for customers with low and highly variable credit scores.
- Investigate the **high churn rate** in German customers and tailor retention strategies for this group.
- Create **targeted retention campaigns** for female customers, addressing their higher churn rate.
- Provide **loyalty programs** and **premium services** for high-balance customers to encourage retention.
- Engage **credit card holders** with personalized offers and rewards programs.
- Offer **age-specific retention strategies** for older customers to reduce churn.
- **Regularly monitor** and **retrain** the churn prediction model, focusing on **recall** and **accuracy**.
- Implement **continuous customer feedback loops** to identify and address reasons for churn.

## Setup and Installation

### **Prerequisites**
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`
