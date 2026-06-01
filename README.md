# Bank Customer Churn Prediction using Machine Learning

## Project Overview

Customer retention plays an important role in businesses that rely on long-term customer relationships. Losing customers directly impacts revenue, customer acquisition costs, and business growth. This project focuses on predicting customer churn using machine learning techniques to identify customers who are likely to leave the bank.

The system analyzes customer information such as demographics, banking activity, financial behavior, and account information to build predictive models capable of estimating churn probability. The final system also provides an interactive prediction interface where users can input customer information and receive churn predictions with confidence scores.

---

## Problem Statement

Banks and subscription-based businesses often struggle to identify customers who are at risk of leaving. Traditional analysis methods are insufficient for detecting complex patterns hidden within customer behavior.

The objective of this project is to develop machine learning models capable of:

* Identifying customers likely to churn
* Comparing multiple machine learning algorithms
* Selecting the best-performing model
* Providing an interactive prediction system

---

## Dataset

Dataset used:

[Kaggle Dataset - Bank Customer Churn Prediction Dataset](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction?utm_source=chatgpt.com)

The dataset contains customer information including:

* Customer demographics
* Credit score information
* Geography and gender
* Account balance
* Number of products
* Active membership status
* Salary information
* Churn label (Exited / Not Exited)

The dataset contains customer attributes commonly used for classification-based churn prediction tasks.

---

## Machine Learning Workflow

### 1. Data Preprocessing

The dataset undergoes preprocessing before model training:

* Missing value inspection
* Removal of irrelevant columns
* Encoding categorical features
* Feature scaling
* Train-test splitting

---

### 2. Feature Engineering

Additional features were created to improve model performance:

* Balance-to-Salary ratio
* Customer age grouping
* Numerical feature transformations

Feature engineering improves the model’s ability to capture behavioral patterns hidden within raw customer information.

---

### 3. Exploratory Data Analysis

Visualization techniques were used to understand:

* Customer churn distribution
* Feature relationships
* Correlation between variables
* Customer behavior patterns

---

### 4. Machine Learning Algorithms Used

Multiple algorithms were trained independently:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

These algorithms were selected to compare linear models, ensemble learning approaches, and boosting techniques. Ensemble methods frequently perform strongly in churn prediction problems.

---

### 5. Model Evaluation

Each model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

Separate evaluation was performed for every algorithm to compare performance fairly.

---

### 6. Model Comparison

All algorithms were compared using evaluation metrics.

The best-performing model was selected based on:

* Predictive performance
* Stability
* Classification effectiveness
* Generalization capability

---

### 7. Interactive Prediction System

The final project includes a prediction interface where users can:

* Enter customer information
* Predict churn probability
* Receive confidence scores
* Run multiple predictions continuously

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter / Google Colab

---

## Project Structure

```
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

## Results

The project demonstrates how machine learning can assist businesses in identifying customers with high churn probability and enable proactive retention strategies.

By combining preprocessing, feature engineering, multiple classification algorithms, and evaluation techniques, the system provides an end-to-end customer churn prediction pipeline.

---

## Future Improvements

Possible future enhancements:

* Hyperparameter optimization
* Deep learning models
* Deployment using web applications
* Real-time prediction APIs
* Advanced feature engineering

---

## Author

Deependra Pandey

Machine Learning Project for Virtual Internship
