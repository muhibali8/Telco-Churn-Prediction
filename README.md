# Telco Customer Churn Prediction

## Project Overview
This project aims to predict whether a customer will churn (leave the company) using machine learning. The goal is to help the company take proactive measures to retain at-risk customers.

**Type:** Classification (Supervised ML)  
**Dataset:** [Telco Customer Churn - Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)  

---

## Objective
- Predict customer churn based on demographic, account, and service information.
- Provide actionable insights for customer retention campaigns.

---

## Key Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values for numeric and categorical features.
   - Encoded categorical features using One-Hot Encoding.
   - Scaled numeric features for model performance.

2. **Modeling**
   - Trained a **Random Forest Classifier** with `class_weight='balanced'` to handle imbalanced data.
   - Tuned **threshold** to optimize F1-score and recall.
   - Evaluated model using **F1-score, recall, and confusion matrix**.

3. **Evaluation Metrics**
   - **Test F1-score:** 0.65  
   - **Recall:** 0.82–0.85  
   - Confusion matrix analyzed to understand misclassifications.

4. **Confusion Matrix Heatmap**

   - Confusion matrix used to analyze churn prediction errors. 

5. **Business Insight**
   - Prioritized catching churners over false positives to minimize customer loss.
   - The model can support targeted retention campaigns to reduce churn.

---

## Tools & Libraries
- Python
- Pandas
- scikit-learn
- Seaborn, Matplotlib
- Jupyter

---

## Usage
1. Clone this repository:  
   ```bash
   git clone <your-repo-link>
