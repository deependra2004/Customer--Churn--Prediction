# Bank Customer Churn Prediction using Machine Learning

## Overview

Customer retention has become one of the most important challenges for financial institutions and subscription-based businesses. Acquiring new customers is often more expensive than retaining existing ones, making churn prediction an essential business problem.

This project develops a machine learning-based customer churn prediction system capable of identifying customers who are likely to discontinue banking services. Multiple machine learning algorithms are trained, evaluated, and compared to select the best-performing predictive model.

The final system provides an interactive prediction interface that allows users to enter customer information and receive churn predictions with confidence scores.

---

# Problem Statement

Banks handle thousands of customers with varying behavioral patterns and financial activities. Identifying customers at risk of leaving manually is difficult because churn behavior depends on multiple interconnected factors.

The primary objectives of this project are:

* Build a customer churn prediction system
* Perform preprocessing and feature engineering
* Train multiple machine learning models
* Compare algorithm performance
* Select the best-performing model
* Develop an interactive prediction interface

---

# Dataset Description

Dataset Source:

https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction

The dataset contains customer banking information used to determine whether customers are likely to exit the service.

## Features Used

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary
* Customer Exit Status (Target Variable)

---

# Machine Learning Pipeline

## 1. Data Preprocessing

The raw dataset undergoes multiple preprocessing operations before model training.

### Steps performed:

* Import dataset
* Handle missing values
* Remove irrelevant columns
* Encode categorical features
* Standardize numerical variables
* Split dataset into training and testing sets

Preprocessing ensures the data becomes suitable for machine learning algorithms.

---

## 2. Exploratory Data Analysis

Visualization techniques were used to understand customer behavior and feature relationships.

### Visualizations Performed:

* Customer churn distribution
* Correlation heatmaps
* Feature distribution analysis
* Customer demographic analysis
* Target variable visualization

Exploratory analysis helps identify hidden patterns and important predictive variables.

---

## 3. Feature Engineering

Additional features were created to improve predictive performance.

### Engineered Features:

### Balance-to-Salary Ratio

Measures customer financial behavior.

```text
BalanceSalaryRatio = Balance / Salary
```

### Age Groups

Customer ages were converted into grouped categories.

* Young Customers
* Middle Age Customers
* Senior Customers

Feature engineering improves model learning capability.

---

## 4. Train-Test Split

Dataset division:

* Training Data = 80%
* Testing Data = 20%

The split ensures unbiased model evaluation.

---

# Machine Learning Models Used

Multiple algorithms were trained independently to compare performance.

## Logistic Regression

Used as the baseline classification model.

Advantages:

* Fast training
* Easy interpretation
* Works well on linear relationships

---

## Random Forest Classifier

Uses multiple decision trees combined together.

Advantages:

* Handles complex patterns
* Reduces overfitting
* Strong predictive performance

---

## Gradient Boosting Classifier

Sequential learning approach that improves weak learners.

Advantages:

* High predictive capability
* Handles nonlinear relationships
* Strong classification performance

---

# Model Evaluation Metrics

Each algorithm was evaluated independently using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* ROC AUC Score
* Classification Report
* Confusion Matrix

These metrics provide a balanced evaluation rather than relying solely on accuracy.

---

# Algorithm Comparison

After training all models, performance comparison was performed.

| Algorithm           | Performance |
| ------------------- | ----------- |
| Logistic Regression | Moderate    |
| Gradient Boosting   | High        |
| Random Forest       | Highest     |

---

# Best Model Selection

## Best Model: Random Forest Classifier

Random Forest was selected as the final model because it produced:

* Highest prediction accuracy
* Better generalization capability
* Lower overfitting
* Better classification performance
* More balanced precision and recall scores

The final interactive prediction system uses Random Forest as the deployment model.

---

# Interactive Prediction System

The project includes a prediction system where users can:

* Enter customer details
* Predict customer churn
* View prediction confidence
* See churn probability
* Run multiple predictions continuously

Example Output:

```text
Prediction: Customer likely to churn

Confidence: 91.7%

Probability of Churn: 91.7%

Probability of Staying: 8.3%
```

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook
* GitHub

---

# Project Structure

```text
Bank-Customer-Churn-Prediction/

│

├── dataset/

├── notebooks/

├── models/

├── README.md

├── requirements.txt

└── churn_prediction.ipynb
```

---

# Applications

Potential applications include:

* Customer retention strategies
* Banking analytics
* Subscription service optimization
* Risk assessment systems
* Business intelligence systems

---

# Future Improvements

Possible future improvements:

* Hyperparameter optimization
* Deep learning models
* Model deployment
* Real-time prediction APIs
* Automated retraining pipelines

---

## Author

Name:

Deependra Pandey

Project:

Bank Customer Churn Prediction using Machine Learning

Program:

Virtual Internship Project

Domain:

Machine Learning

Tools & Environment:

Python, Google Colab, Scikit-Learn, GitHub

---

## License

This project is licensed under the MIT License and is intended primarily for academic, educational, and research purposes.

Dataset rights and ownership remain with their respective creators and sources.
