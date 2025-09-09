# telco-churn-prediction

- Overview

This project predicts customer churn (whether a customer will leave the service) using the Telco Customer Churn dataset.
Machine learning models such as Logistic Regression and Random Forest were trained and evaluated.

- Steps in the Project

1-Data Preprocessing:
  - Removed customerID
  - Converted TotalCharges to numeric
  - Handled missing values

2-Feature Engineering:
  - One-Hot Encoding for categorical features
  - Train-test split

3-Models Trained:
  - Logistic Regression
  - Random Forest
 
4-Evaluation Metrics:
  - Accuracy
  - Confusion Matrix
  - ROC-AUC Score
  
- Results
  - Logistic Regression → Accuracy: ~74%, ROC-AUC: ~0.84
  - Random Forest → Accuracy: ~79%, ROC-AUC: ~0.82

- Files in Repository
  - Telco_Churn_Prediction.ipynb → Jupyter Notebook with code and results
  - Dataset (from Kaggle: Telco Customer Churn)

- How to Run
  1- Clone the repository:
      git clone https://github.com/nidhideval/telco-churn-prediction.git
    - kaggle link:https://www.kaggle.com/code/nidhideval/telco-churn-prediction
  2- Open the notebook in Jupyter or Google Colab.
  3- Run all cells to reproduce results.

 - License
    This project is licensed under the MIT License – free to use and share with credit.
