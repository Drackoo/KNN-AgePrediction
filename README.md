# 🧠 Age Prediction Using KNN Classifier (NHANES Dataset)

This project implements a machine learning model using the **K-Nearest Neighbors (KNN)** algorithm to predict a person's age group based on health and biometric features from the **National Health and Nutrition Examination Survey (NHANES) 2013-2014** dataset.

---

## 📂 Dataset
- **Source:** UCI Machine Learning Repository  
- **Name:** National Health and Nutrition Health Survey 2013-2014 (NHANES) Age Prediction Subset  
- **Features:** Physiological metrics (blood pressure, cholesterol, blood sugar, BMI, physical activity, etc.)

---

## 🎯 Objectives
- Classify individuals into age groups using KNN
- Evaluate and improve model performance using **cross-validation** and **hyperparameter tuning**
- Visualize performance metrics

---

## 🛠️ Methods and Tools
- Language: **Python**
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`
- Tools: **Jupyter Notebook / Google Colab**
- Custom-built **KNN Classifier** (no external ML libraries used for modeling)
- **5-Fold Cross-Validation**
- Performance Metrics: Accuracy, F1 Score

---

## 📊 Steps Overview

1. **Setup & Data Import**
   - Import libraries and fetch NHANES dataset
2. **Exploratory Data Analysis**
   - Box plots for feature distribution
3. **Preprocessing**
   - Feature scaling (Standard Scaler)
   - K-Fold data splitting
4. **Modeling**
   - Custom KNN algorithm with Euclidean distance
5. **Evaluation**
   - 5-fold cross-validation on both train & test data
   - Metrics: Accuracy & F1 Score
6. **Hyperparameter Tuning**
   - Tested `k` values from 1 to 15
   - Best accuracy at `k = 8` with ~84%

---

## 📈 Results
- **Best Accuracy:** ~84%
- **Best F1 Score:** ~84%
- **Optimal K Value:** 8
- KNN performs well on age classification, especially after tuning the `k` parameter

---

## 📌 How to Run

```bash
# Install dependencies
pip install ucimlrepo pandas numpy matplotlib scikit-learn

# Run the script
python KNN_AGE-PREDICTION.py
```

---

## 👥 Team Members
- Teuku Muhammad Ibrahim – 1301223159  
- Jason Jeremy B.B. – 1301223110  
- M. Hibban Musyaffa – 1301223177  

---

## 📌 Notes
This project was completed as part of the **"Pengantar AI"** course at our university. It focuses on fundamental machine learning concepts and manual model implementation.
