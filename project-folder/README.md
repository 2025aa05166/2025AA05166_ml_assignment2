# 📘 Machine Learning Assignment – 2  
**BITS WILP | M.Tech (AIML)**  
**Roll No.: 2025AA05166**

---
# 1. GitHub Repository Link
https://github.com/2025aa05166/2025AA05166_ml_assignment2/edit/main/project-folder
# 2. Live Streamlit App Link 
https://2025aa05166mlassignment2.streamlit.app/
# 3. Screenshot of assignment execution on BITS Virtual Lab
![Screenshot 2026-02-14 230425](https://github.com/user-attachments/assets/e0fea43a-5072-4af9-bbe7-b88182f3faac)


## a. Problem Statement

The objective of this assignment is to design, implement, evaluate, and deploy multiple machine learning classification models on a real-world dataset. The task involves building six different classification algorithms, comparing their performance using standard evaluation metrics, and deploying the trained models through an interactive Streamlit web application.

This assignment demonstrates an end-to-end machine learning workflow including data preprocessing, model training, evaluation, visualization, and deployment.

---

## b. Dataset Description 

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

## c. Models Used and Evaluation Metrics

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
| Logistic Regression | 0.810 | 0.930 | 0.762 | 0.914 | 0.831 | 0.631 |
| Decision Tree | 0.985 | 0.986 | 1.000 | 0.971 | 0.986 | 0.971 |
| kNN | 0.863 | 0.963 | 0.874 | 0.857 | 0.865 | 0.727 |
| Naive Bayes | 0.829 | 0.904 | 0.807 | 0.876 | 0.840 | 0.660 |
| Random Forest (Ensemble) | 1.000 | 1.000 | 1.000 | 1.000 | 1.000 | 1.000 |
| XGBoost (Ensemble) | 1.000 | 1.000 | 1.000 | 1.000 | 1.000 | 1.000 |

---

## d. Observations on Model Performance

| ML Model Name | Observation |
|--------------|------------|
| Logistic Regression | Provided a stable baseline with high recall but comparatively lower precision due to its linear decision boundary. |
| Decision Tree | Achieved very high accuracy, indicating strong learning capacity but with a high risk of overfitting. |
| kNN | Delivered balanced performance across metrics, benefiting from feature scaling but sensitive to neighborhood selection. |
| Naive Bayes | Showed reasonable performance with fast computation, though limited by its feature independence assumption. |
| Random Forest (Ensemble) | Achieved perfect scores across all metrics, demonstrating strong ensemble learning but potential overfitting. |
| XGBoost (Ensemble) | Delivered the best overall performance by capturing complex patterns through boosting, though perfect scores suggest possible overfitting. |

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
