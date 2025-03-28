# Bank Customer Churn Prediction

## 📌 Project Overview
Customer churn is a significant challenge for banks, impacting revenue and customer retention. This project aims to predict customer churn using both **Machine Learning (ML) models** and **Artificial Neural Networks (ANN)**, enabling proactive retention strategies.

## 📊 Dataset
The dataset contains customer banking information, including:
- **Customer Details**: `CustomerID`, `Name`, `Age`, `Gender`, `Geography`
- **Account Information**: `Credit Score`, `Balance`, `Number of Products`, `Is Active Member`
- **Transaction & Loan History**: `Tenure`, `Estimated Salary`, `Has Credit Card`
- **Target Variable**: `Exited` (1 = Yes, 0 = No)

## 🔍 Data Preprocessing 
- Checked for **missing values**
- Dropped **irrelevant columns** from the data.

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of numerical and categorical variables.
- Used **correlation matrix** and feature engineering techniques.

## 🔍 Feature Engineering 
- **Handled outliers** 
- Performed **feature encoding** for categorical variables.
- Applied **scaling** to numerical features.

## 🚀 Models Implemented
### 1️⃣ Machine Learning Models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **XGBoost**
- **Support Vector Machine (SVM)**

### 2️⃣ Artificial Neural Network (ANN):
- **Input Layer**: Processed features
- **Hidden Layers**: Multiple dense layers with ReLU activation
- **Output Layer**: Sigmoid activation (Binary classification)
- **Optimizer**: Adam
- **Loss Function**: Binary Crossentropy
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, AUC-ROC

## 📈 Model Evaluation
- Compared ML and ANN models using:
  - **Confusion Matrix**
  - **Accuracy, Precision, Recall, and F1-score**
  - **AUC-ROC Curve**
- Used **Feature Importance (ML models)** and **SHAP values (ANN)** for interpretability.

## 🔥 Key Insights
- Customers with **low engagement** are more likely to churn.
- Customers with **low credit scores and fewer products** tend to leave the bank.
- Active members have a significantly lower churn rate.
