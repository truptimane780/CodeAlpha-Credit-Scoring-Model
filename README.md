# CodeAlpha Credit Scoring Model

## Project Overview

This project develops a machine learning model for predicting creditworthiness and loan approval using financial and applicant-related data.

The target variable used in this project is `Loan_Approved`.

## Objective

The main objective of this project is to build and evaluate machine learning models that can predict whether a loan application will be approved based on the available applicant and financial features.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

The following machine learning algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Random Forest

## Data Processing

The project includes:

- Data loading and inspection
- Missing-value handling
- Exploratory Data Analysis (EDA)
- Categorical variable encoding
- Feature scaling
- Train-test split
- Feature engineering

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Random Forest Results

| Metric | Score |
|---|---:|
| Accuracy | 90.00% |
| Precision | 85.66% |
| Recall | 90.00% |
| F1-Score | 87.72% |
| ROC-AUC | 90.44% |

## Dataset

The project uses the `loan_approval_data.csv` dataset.

The target variable is `Loan_Approved`, which represents the loan approval outcome used for the prediction task.

## Project Files

- `credit_wise.ipynb` — Complete machine learning notebook
- `loan_approval_data.csv` — Dataset used for the project
- `README.md` — Project documentation

## Conclusion

The implemented machine learning models were evaluated using multiple classification metrics. The Random Forest model achieved 90.00% accuracy and a ROC-AUC score of 90.44% on the test data.

The project demonstrates the application of machine learning techniques for analyzing financial and applicant-related data and predicting loan approval outcomes.
