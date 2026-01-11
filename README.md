# 🫘 Kidney Stone Prediction Using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project focuses on predicting the **presence or absence of kidney stones** using urine analysis data and the **K-Nearest Neighbors (KNN)** machine learning algorithm.  
The goal is to demonstrate a complete end-to-end ML workflow including data exploration, visualization, preprocessing, model training, evaluation, and tuning.

---

## 🎯 Problem Statement
Kidney stones are a common medical condition that can be detected through urine-related parameters.  
This project aims to build a **binary classification model** that predicts whether a patient has a kidney stone based on measurable urine features.

---

## 📊 Dataset
- **Source:** Public medical dataset (Excel format)
- **Rows:** 12,952
- **Features:**  
  - Specific gravity of urine  
  - pH of urine  
  - Osmolarity of urine  
  - Conductivity of urine  
  - Concentration of urea in urine  
  - Concentration of calcium in urine  
- **Target Variable:**  
  - Presence of stone  
  - Absence of stone  

---

## 🔍 Exploratory Data Analysis (EDA)
- Checked missing values and data types
- Target class distribution analysis
- Correlation heatmap
- Scatter matrix (pairplot-style)
- Boxplots for numerical features

---

## 🛠️ Data Preprocessing
- Removed irrelevant index column
- Encoded categorical target variable
- Feature scaling using **StandardScaler**
- Train–test split (80/20)

---

## 🤖 Model Used
- **Algorithm:** K-Nearest Neighbors (KNN)
- **Model Type:** Classification
- **Reason:**  
  KNN works well for distance-based classification problems and is effective after proper feature scaling.

---

## 📈 Model Evaluation
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve & AUC Score
- k-Fold Cross Validation

---

## 🔁 Hyperparameter Tuning
- Tested multiple values of **k**
- Selected optimal k based on accuracy and cross-validation
- Visualized accuracy vs k curve

---

## ✅ Results
- Achieved strong classification performance
- Feature scaling significantly improved accuracy
- Cross-validation confirmed model stability

---

## 🧠 Key Insights
- Urine chemical properties have a measurable relationship with kidney stone presence
- Proper preprocessing is crucial for KNN
- Optimal k balances bias and variance effectively

---

## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---
## 📦 Kidney-Stone-KNN
- │
- ├── 📄 Kidney_Stone_KNN_Assignment.ipynb
- ├── 📄 README.md
- └── 📊 Dataset (Excel)
---

---

## 🚀 Conclusion
This project demonstrates how machine learning can assist in **medical risk prediction** using structured clinical data.  
The approach can be extended to other healthcare classification problems.

---

⭐ *If you find this project helpful, feel free to star the repository!
