# 📘 Project Overview

- This project focuses on building a machine learning system to predict customer churn — i.e., whether a customer is likely to stop using a company’s service. 
- It uses end-to-end data preprocessing, feature engineering, model selection, hyperparameter tuning, and evaluation pipelines with Scikit-learn.
- The dataset used represents a telecom company’s customer base, including attributes like tenure, billing method, contract type, and internet service details.

---

## 🎯 Objective
- To accurately predict whether a customer will churn based on their usage patterns, demographic information, and service-related factors.
- The goal is to help businesses identify at-risk customers early and implement retention strategies.

## 🧠 Key Features

- ✅ Complete preprocessing pipeline using ColumnTransformer and Pipeline
- ⚙️ Automatic encoding and scaling of categorical and numerical columns
- 🔍 Model training using multiple classifiers:

---

## 🤖 Models

- K-Nearest Neighbors (KNN)
- SVC (Support Vector Classifier)
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting
- Voting Classifier
- XGBoost 
- CatBoostClassifier (if required)

---

## 🔧 Hyperparameter tuning using GridSearchCV

- 📊 Model evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC) using classification_report
- 📈 Visual analysis (correlation heatmap, churn distribution, feature importance, PieChart, Histogram)

## 🧪 Model Performance
|          Model          | Accuracy| 
|----------------------- -|---------|
|  KNeighborClassifier    |   0.78  |
|  SVC                    |   0.79  |
|  LogisticRegression     |   0.80  |
|  RandomForestClassifier |  0.755  |
|  VotingClassifier       |  0.792  |
|  XGBoost                |   0.75  |
|  CatBoostClassifier     |   0.79  |


## 🔥 Highlights

- Modular design — every model has its own pipeline
- Reusable preprocessing system
- Hyperparameter search using GridSearchCV
- Handles categorical & numerical data seamlessly
- Prevents data leakage by integrating preprocessing into training pipeline


1. **Clone the repository**:
   ```bash
      git clone https://github.com/sunodmongia/Customer_Churn_Prediction.git
      cd Customer_Churn_Prediction


2. **Creating Virtual Environment**
    ```bash
       python -m venv venv
       .\env\Scripts\activate  # On Windows
        source venv/bin/activate  # On Mac/Linux

3. **Installing Dependencies**
    ```bash
       pip install -r requirements.txt


