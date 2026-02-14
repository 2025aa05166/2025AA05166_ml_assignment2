# 📘 Machine Learning Assignment – 2  
**BITS WILP | M.Tech (AIML / DSE)**  
**Roll No.: 2025AA05166**

---

## a. Problem Statement

The objective of this assignment is to design, implement, evaluate, and deploy multiple machine learning classification models on a real-world dataset. The task involves building six different classification algorithms, comparing their performance using standard evaluation metrics, and deploying the trained models through an interactive Streamlit web application.

This assignment demonstrates an end-to-end machine learning workflow including data preprocessing, model training, evaluation, visualization, and deployment.

---

## b. Dataset Description  **[1 Mark]**

The dataset used for this assignment is the **Heart Disease Dataset** obtained from **Kaggle** (`johnsmith88/heart-disease-dataset`).

### Dataset Characteristics:
- **Problem Type:** Binary Classification  
- **Target Variable:** `num`  
  - `0` → No heart disease  
  - `1` → Presence of heart disease  
- **Number of Features:** 13  
- **Number of Instances:** 1000+  
- **Feature Types:** Numerical and Categorical  

The dataset was split into **80% training data** and **20% testing data** using stratified sampling.

---

## c. Models Used and Evaluation Metrics  **[6 Marks]**

The following six classification models were implemented on the same dataset:

1. Logistic Regression  
2. Decision Tree Classifier  
3. K-Nearest Neighbors (kNN)  
4. Naive Bayes (Gaussian)  
5. Random Forest (Ensemble)  
6. XGBoost (Ensemble)

### 📊 Model Comparison Table

| ML Model Name | Accuracy | AUC | Precision | Recall | F1 Score | MCC |
|--------------|----------|-----|-----------|--------|----------|-----|
| Logistic Regression | 0.86 | 0.92 | 0.85 | 0.89 | 0.87 | 0.72 |
| Decision Tree | 0.80 | 0.82 | 0.79 | 0.81 | 0.80 | 0.60 |
| kNN | 0.83 | 0.86 | 0.82 | 0.84 | 0.83 | 0.65 |
| Naive Bayes | 0.78 | 0.81 | 0.77 | 0.79 | 0.78 | 0.55 |
| Random Forest (Ensemble) | 0.88 | 0.92 | 0.87 | 0.89 | 0.88 | 0.75 |
| XGBoost (Ensemble) | 0.90 | 0.94 | 0.89 | 0.91 | 0.90 | 0.78 |

---

## d. Observations on Model Performance  **[3 Marks]**

| ML Model Name | Observation |
|--------------|------------|
| Logistic Regression | Stable baseline model with good interpretability. |
| Decision Tree | Interpretable but prone to overfitting. |
| kNN | Balanced performance but sensitive to scaling. |
| Naive Bayes | Fast but limited by independence assumption. |
| Random Forest (Ensemble) | Strong performance with reduced overfitting. |
| XGBoost (Ensemble) | Best overall performance due to boosting. |

---

## 📌 Streamlit Application Details

- Dataset upload (test data only)
- Model selection dropdown
- Evaluation metrics display
- Confusion matrix and classification report
- Deployed using Streamlit Community Cloud

---

## 📂 Repository Structure

```
project-folder/
│-- app.py
│-- requirements.txt
│-- README.md
│-- model/
│-- data/
```

---

## ✅ Final Notes

- Assignment executed on **BITS Virtual Lab**
- Screenshot included in PDF submission
- Original work following academic integrity guidelines
