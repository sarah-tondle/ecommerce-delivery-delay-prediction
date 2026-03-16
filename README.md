# Predicting Late Deliveries in E-Commerce Using Machine Learning

## Project Overview

Delivery delays are a major challenge in e-commerce logistics and can negatively impact customer satisfaction and operational efficiency.

This project uses machine learning techniques to predict whether an e-commerce order will be delivered late based on order, product, and delivery-related features.

The analysis was performed using the Brazilian E-Commerce Public Dataset by Olist available on Kaggle.

---

## Dataset

Dataset Source:
Brazilian E-Commerce Public Dataset by Olist (Kaggle)

The dataset contains information about:
- Orders
- Customers
- Products
- Order items
- Reviews
- Delivery timestamps

Multiple datasets were merged to create a final dataset used for machine learning.

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis
5. Machine Learning Model Development
6. Model Evaluation
7. Feature Importance Analysis

---

## Machine Learning Models Used

Two models were implemented and compared:

### Random Forest Classifier
A tree-based ensemble model that combines multiple decision trees to improve prediction performance.

### Logistic Regression
A statistical model commonly used for binary classification problems.

---

## Model Evaluation

Models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- AUC score

Random Forest achieved better overall performance compared to Logistic Regression.

---

## Key Insights

- Estimated delivery time is the strongest predictor of delivery delays.
- Customer location impacts delivery efficiency.
- Product price also contributes to delivery patterns.
- Machine learning can help identify orders at risk of late delivery.

---

## Tools and Technologies

Python  
Pandas  
NumPy  
Scikit-learn  
Matplotlib / Seaborn  
Google Colab

---

## Repository Contents

- Jupyter Notebook containing the complete analysis
- Research project documentation
- Visualizations and model evaluation results

---

## Future Improvements

- Implement advanced models such as XGBoost
- Address dataset imbalance using techniques like SMOTE
- Build an interactive dashboard for real-time delivery prediction

---

## Author

Sarah Tondle  
MSc Data Science
