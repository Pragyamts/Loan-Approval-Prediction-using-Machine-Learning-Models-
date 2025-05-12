# Loan Approval Prediction using Machine Learning Models
This repository contains the project files for the Loan Approval Prediction analysis, conducted to evaluate financial and demographic factors influencing loan approval decisions. The objective of this project is to develop predictive models to assist financial institutions in assessing credit risk effectively.
## Project Overview
In the financial sector, loan approval decisions are critical and involve evaluating various financial and demographic parameters. This project leverages statistical learning algorithms to predict loan approval status based on a dataset of 20,000 synthetic records. It compares the performance of three models:

-Logistic Regression

-Support Vector Machine (SVM)

-Random Forest Classifier
## Key Objectives:

-Identify significant predictors of loan approval.

-Develop, train, and evaluate multiple machine learning models.

-Compare model performance based on accuracy, precision, recall, F1 Score, and AUC-ROC.

-Analyze feature importance to understand the drivers of loan approval.
## Methodology
### Data Preprocessing:

Data Reduction: Removal of irrelevant features.

Missing Values & Outlier Analysis: No missing values or significant outliers detected.

Feature Engineering: One-Hot Encoding for categorical variables, Standard Scaling for continuous variables.
### Exploratory Data Analysis (EDA):

Descriptive statistics for feature distribution analysis.

Correlation matrix to detect multicollinearity and redundant features.

Feature selection based on correlation with the target variable.

### Model Training & Evaluation:

Data Split: 60% training and 40% testing.

Models: Logistic Regression, SVM, Random Forest.

Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, AUC-ROC.

### Feature Importance Analysis:

Comparison of feature importance across the three models to identify key predictors.

Visualization of the impact of top features like Risk Score, Total Debt to Income Ratio, and Annual Income.
## Results & Findings
### Model Comparison:

Logistic Regression: 98% accuracy, strong interpretability through feature coefficients.

SVM: 98% accuracy, high precision and balanced recall.

Random Forest: 100% training accuracy, 98% testing accuracy, highest feature importance for Risk Score.

### Key Findings:

The Risk Score emerged as the most influential predictor across all models.

Random Forest demonstrated the best overall performance, though potential overfitting was observed.

Logistic Regression provided the most interpretable model, offering direct insights into feature impact.
