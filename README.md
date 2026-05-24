# Customer Churn Prediction

https://miro.medium.com/v2/resize:fit:1400/format:webp/1*ctP13Q-tsQXW9E8L6hbi4Q.png


## Overview
This project focuses on predicting customer churn using machine learning techniques and evaluating model performance through ROC-AUC analysis. The goal is to identify customers who are likely to leave a service so businesses can improve customer retention strategies.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## Objective
The main objective of this project is to:
- Predict customer churn using machine learning models
- Analyze customer behavior patterns
- Improve business decision-making using predictive analytics

---

## Dataset
The dataset contains customer-related information such as:
- Customer demographics
- Account information
- Service usage
- Subscription details
- Churn status

---

## Workflow

### Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Scaled numerical features
- Cleaned and prepared data for modeling

### Exploratory Data Analysis (EDA)
- Analyzed churn distributions
- Visualized customer behavior trends
- Identified important churn-related features

### Machine Learning Models
Implemented models including:
- Logistic Regression
- Random Forest
- XGBoost

### Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC Curve
- ROC-AUC Score

---

## Results
The customer churn prediction model achieved:

- **ROC-AUC Score:** **0.85**

The ROC curve indicates strong classification performance and shows that the model performs significantly better than random prediction in identifying churned customers.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```bash
├── Customer_Churn.ipynb   # Main notebook
├── data/                  # Dataset files
├── models/                # Saved models
├── images/                # Graphs and visualizations
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
