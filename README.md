# 💳 Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using **Machine Learning models**.  
The dataset is highly imbalanced, and the project explores various techniques to handle imbalance while maintaining high accuracy in fraud detection.

---

## 📂 Dataset
- The dataset used is the **Kaggle Credit Card Fraud Detection Dataset** (European transactions in September 2013).  
- It contains **284,807 transactions**, out of which only **492 are frauds (0.172%)**.

---

## 🛠️ Technologies Used
- **Python**
- **NumPy, Pandas** – Data preprocessing & manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning models
- **Imbalanced-learn (SMOTE, undersampling, oversampling)**

---

## 🔍 Project Workflow
1. **Data Exploration & Cleaning**
   - Checked missing values and class distribution.
   - Performed scaling and standardization.

2. **Exploratory Data Analysis (EDA)**
   - Visualized transaction amounts and class imbalance.
   - Correlation analysis of anonymized features.

3. **Handling Imbalanced Data**
   - Tried **undersampling, oversampling, and SMOTE** to balance classes.

4. **Model Building**
   - Trained multiple ML models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine (SVM)
     - XGBoost

5. **Model Evaluation**
   - Metrics used: **Accuracy, Precision, Recall, F1-score, ROC-AUC**
   - Emphasis on **Recall** (minimizing false negatives).

---

## 📊 Results
- The best-performing model achieved:
  - **High Recall on Fraudulent Transactions**
  - **Balanced Precision and F1-score**

---

## 🚀 Future Improvements
- Hyperparameter tuning with GridSearchCV / RandomizedSearchCV.
- Using deep learning models (LSTM, Autoencoders).
- Real-time fraud detection pipeline with **Kafka + Spark Streaming**.

---
