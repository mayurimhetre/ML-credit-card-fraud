# ML-credit-card-fraud-detection

Dataset Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Credit Card Fraud Detection Dataset

- This dataset contains **284,807 anonymized credit card transactions** made by European cardholders, with a very small fraction labeled as fraudulent, making it highly imbalanced.  
- Most features are **PCA-transformed numerical variables (V1–V28)**, along with `Time` and `Amount`, to protect sensitive information.  
- The objective is to build a **binary classification model** that accurately identifies **fraudulent transactions (Class = 1)** among legitimate ones (Class = 0).

---

## Model Used

In this project, **Logistic Regression** was implemented to perform binary classification and detect fraudulent credit card transactions.  
It provides a simple yet effective baseline model for handling high-dimensional, PCA-transformed features and evaluating performance on imbalanced data.

