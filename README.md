# credit_fraud
A machine learning project for detecting fraudulent credit card transactions using Python.

------------------------------------------------------------------------------------------

## Dataset
- **Number of Records**: 284,807 transactions
- **Number of Features**: 31 
- **Target Variable**:
  - 0: Non-fraudulent transactions
  - 1: Fraudulent transactions
-----------------------------------------------------------------------------------------

## Project Overview
This project predicts fraudulent credit card transactions using machine learning models. 
It uses a highly imbalanced dataset to identify patterns indicative of fraudulent behavior. 
The primary metrics used are precision, recall and F1-score, 
with an emphasis on F1-score, for evaluation.

------------------------------------------------------------------------------------------

## Modeling Approach
1. **Exploratory Data Analysis (EDA)**: Visualizations, correlation analysis.
2. **Data Preprocessing**: SMOTE oversampling and undersampling for handling class imbalance.
3. **Modeling**: Various models were evaluated:
   - Logistic Regression
   - Support Vector Machines (SVM)
   - Random Forest
   - XGBoost
4. **Evaluation Metrics**: Precision, Recall, F1-Score.

------------------------------------------------------------------------------------------

## Running the model-pipeline:
   The creditcard.csv file contains the dataset. The project notebook is named "credit_card.ipynb".
   After loading the dataset, some exploratory Data Analysis is performed.
   Beyond which data is transformed for the models. 
   After transformation, the models are created and evaluated by the specified parameters. 
   Finally, the most appropriate model is saved depending on the evaluation metric.
