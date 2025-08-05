# Bank Loan Approval Prediction using Machine Learning

## 📌 Overview
This project predicts whether a loan application should be approved or not based on applicant details such as income, credit history, and demographic data.  
It uses **Logistic Regression**, **Random Forest**, and **XGBoost** models, with **SMOTE** applied to handle class imbalance.

---

## 🚀 Features
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training & Evaluation
- Class Imbalance Handling (SMOTE)
- Hyperparameter Tuning (GridSearchCV)
- ROC Curve & AUC Score Evaluation
- Model Saving for Deployment

---

## 📂 Dataset
The dataset `Bankloan.csv` contains:
- Applicant details (Income, Education, Marital Status, etc.)
- Loan attributes (Amount, Term, Credit History)
- Target variable: Loan Status (Y/N)

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost, imbalanced-learn
- **Jupyter Notebook** for analysis
- **Joblib / Pickle** for model persistence

---

## 📊 Results
- **Best Model**: XGBoost
- **Accuracy**: 78%
- **AUC Score**: ~0.75
- Improved recall for approved loan cases after applying SMOTE.

---

## 📁 Project Structure
