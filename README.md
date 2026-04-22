# 📊 Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn for a telecom company using Machine Learning techniques. By analyzing customer demographics, service usage, billing information, and support interactions, the model identifies whether a customer is likely to leave the service.

---

## Project Overview

Customer churn is a major challenge for subscription-based businesses. Retaining customers is often more cost-effective than acquiring new ones.

In this project, we:

- Performed data cleaning and preprocessing
- Analyzed customer behavior patterns
- Handled class imbalance in the dataset
- Applied Machine Learning models for churn prediction
- Evaluated model performance using standard metrics

---

## Dataset Information

The dataset contains **3333 customer records** and **33 features**, including:

### Customer Details
- Gender
- Senior Citizen
- Marital Status
- Dependents
- Tenure

### Services Used
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV / Movies

### Billing & Usage
- Contract Type
- Paperless Billing
- Payment Method
- Total Revenue
- Call Minutes (Day / Evening / Night / International)
- Number of Calls
- Customer Service Calls

### Target Variable
- **Churn**
  - Yes = Customer left
  - No = Customer stayed

:contentReference[oaicite:0]{index=0}

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models Used

###  Logistic Regression
Used as a baseline classification model.

###  Random Forest Classifier
Used for improved accuracy and feature importance analysis.

###  XGBoost
Used for further improved accuracy and feature importance analysis.

---

## Workflow

### 1. Data Loading
Imported dataset using Pandas.

### 2. Exploratory Data Analysis
- Checked shape of dataset
- Verified missing values
- Analyzed churn distribution
- Reviewed statistical summaries

### 3. Data Preprocessing
- Label Encoding for categorical columns
- Feature scaling using StandardScaler
- Balanced target classes by sampling

### 4. Model Training
Split data into training and testing sets using:

- `train_test_split()`

### 5. Model Evaluation
Measured performance using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Goal of the Project

To help telecom companies:

- Identify customers at risk of leaving
- Improve retention strategies
- Reduce revenue loss
- Enhance customer satisfaction

---

## How to Run

```bash
pip install pandas numpy scikit-learn openpyxl
jupyter notebook
```
