# Credit-Card-Fraud-Detection
Detect fraudulent credit card transactions using machine learning models such as Logistic Regression, SVM, Random Forest, and XGBoost. This project focuses on handling class imbalance using UnderSampling and evaluating model performance with accuracy, precision, recall, and F1-score. 

## Problem Statement

Credit card fraud is a significant issue in the financial sector. The goal is to build a machine learning model that can effectively identify fraudulent transactions while minimizing false positives.

---

##  Dataset

- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions
- **Features**: 
  - `Time`, `Amount`, `V1` to `V28` (PCA components)
  - `Class` (0 = Non-Fraud, 1 = Fraud)

---
## Steps Followed

1. **Load all the Dependencies**
   - Numpy,Pandas
   - Classification Models
   - Classification Metrics
    
2. **Data Exploration**
   - Checked for null values
   - Examined class distribution

3. **Preprocessing**
   - Standardization of `Amount` and `Time` features

4. **Handling Imbalanced Data**
   - Applied **UnderSampling Technique** to oversample minority class
   - Also tested **Means** for comparison

5. **Model Training**
   - Trained multiple models:
     - **Logistic Regression**
     - **Support Vector Machine (SVM)**
     - **Random Forest**
     - **XGBoost**

6. **Model Evaluation**
   - Used metrics:
     - **Confusion Matrix**
     - **Accuracy**
     - **Precision**
     - **Recall**
     - **F1 Score**
