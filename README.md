# 💳 Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning algorithms. It tackles real-world challenges such as extreme class imbalance and aims to build models that can accurately detect fraud while minimizing false positives.

---

## 📊 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 284,807 transactions
- **Fraudulent Cases:** 492 (approx. 0.172%)
- **Features:** 30 numerical features (anonymized using PCA), including `Time` and `Amount`

---

## 🎯 Objective

Build a machine learning model to identify fraudulent credit card transactions with a focus on:
- Handling imbalanced data
- Maximizing recall and precision for fraud class
- Interpreting model performance using proper metrics

---

## 🚀 Workflow

### 1. 📌 Data Exploration
- Class distribution
- Correlation heatmap
- Visualization of transaction amount/time

### 2. 🧹 Preprocessing
- Feature scaling using `StandardScaler`
- SMOTE oversampling to balance classes

### 3. 🧠 Modeling
- Logistic Regression
- Decision Tree
- Random Forest
- Optional: XGBoost, LightGBM

### 4. 📈 Evaluation
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC Curve and AUC
- Cross-validation

---

## ✅ Results

- Improved recall and F1-score on minority class (fraud)
- Reduced false negatives using threshold tuning
- SMOTE significantly improved model balance

---

## 🧰 Tech Stack
- **Languages:** Python
- **Libraries:** 
  - pandas, numpy, matplotlib, seaborn
  - scikit-learn
  - imbalanced-learn (SMOTE)
- **Tool:** Jupyter Notebook

---

## 🛠️ How to Run

1. Clone the repository

2. Install dependencies 

3. Run the notebook 

## 📌 Learnings
-Tackling highly imbalanced datasets
-Using SMOTE for synthetic oversampling
-Understanding evaluation metrics for anomaly detection
-Model interpretability for critical domains like finance








