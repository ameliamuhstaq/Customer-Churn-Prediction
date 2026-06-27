Customer Churn Prediction using Machine Learning

Project Overview

Customer churn prediction is a machine learning project that predicts whether a customer will leave a service or continue using it.This project uses the Telco Customer Churn dataset and applies data preprocessing, exploratory data analysis, and machine learning techniques to build a prediction model.

 Problem Statement

Companies lose revenue when customers stop using their services. Predicting customers who are likely to churn helps businesses take preventive actions and improve customer retention.

 Dataset

Dataset:
Telco Customer Churn Dataset

The dataset contains customer information including:

 Customer demographics
 Account information
 Service usage details
 Contract details
 Monthly charges
 Churn status

Technologies Used

Python

Libraries:

 Pandas
 NumPy
 Matplotlib
 Seaborn
 Scikit-learn
 KaggleHub

Machine Learning Algorithm:

 Random Forest Classifier

 Project Workflow

1. Data Collection

Dataset downloaded from Kaggle.

2. Data Cleaning

Performed:

 Removed customer ID column
 Converted Total Charges into numeric format
 Filled missing values
 Converted churn labels into binary values

3. Exploratory Data Analysis

Created visualizations:

 Customer churn distribution
 Correlation heatmap
 Feature importance analysis

4. Data Preprocessing

Performed:

 Label Encoding
 Feature scaling
 Train-test split

5. Model Training

Algorithm:

Random Forest Classifier

6. Model Evaluation

Evaluation metrics:

 Accuracy Score
 Classification Report
 Confusion Matrix

 Results

The model successfully predicts customer churn with good accuracy.

Generated outputs:

 Accuracy visualization
 Confusion matrix
 Feature importance chart
 Classification report

---

 Project Screenshots

Churn Distribution

![Churn Distribution](screenshots/churn_distribution.png)

Correlation Heatmap

![Correlation Heatmap](screenshots/correlation_heatmap.png)

 Model Accuracy

![Accuracy](screenshots/model_accuracy.png)

Confusion Matrix

![Confusion Matrix](screenshots/confusion_matrix.png)

### Feature Importance

![Feature Importance](screenshots/feature_importance.png)
 Files Included


Customer_Churn_Prediction.ipynb
customer_churn_dataset.csv
customer_churn_model.pkl
scaler.pkl
classification_report.txt
screenshots/

