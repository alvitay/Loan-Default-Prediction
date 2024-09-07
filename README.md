# Loan Default Prediction - Home Equity Dataset

## Problem Statement

A bank's consumer credit department aims to streamline the decision-making process for approving home equity lines of credit. To achieve this, they will adopt the Equal Credit Opportunity Act's guidelines to establish an empirically derived and statistically sound credit-scoring model. The model will be based on data from the bank’s existing loan underwriting process for recent applicants. The objective is to develop a predictive model that is interpretable enough to justify any adverse behavior (rejections) while determining the likelihood of a client defaulting on their loan.

## Objective

The objective of this project is to build a **classification model** that predicts which clients are likely to default on their loan. Additionally, the project will aim to provide recommendations to the bank on the important features to consider while approving loans.

## Dataset Overview

The Home Equity dataset (HMEQ) contains baseline and loan performance information for recent home equity loans. The target variable (`BAD`) is a binary indicator that reflects whether an applicant has defaulted or been severely delinquent. There are 12 input variables available for each applicant.

### Data Dictionary:

- **BAD**: Target variable (1 = Client defaulted on loan, 0 = Loan repaid)
- **LOAN**: Amount of the loan approved
- **MORTDUE**: Amount due on the existing mortgage
- **VALUE**: Current value of the property
- **REASON**: Reason for the loan request (`HomeImp` = home improvement, `DebtCon` = debt consolidation)
- **JOB**: Type of job the applicant holds (e.g., manager, self-employed, etc.)
- **YOJ**: Years at the current job
- **DEROG**: Number of major derogatory reports (indicating serious delinquency or late payments)
- **DELINQ**: Number of delinquent credit lines
- **CLAGE**: Age of the oldest credit line in months
- **NINQ**: Number of recent credit inquiries
- **CLNO**: Number of existing credit lines
- **DEBTINC**: Debt-to-income ratio (monthly debt payments divided by gross monthly income)

## Project Workflow

1. **Data Preprocessing**: Handle missing values, standardize numeric variables, and encode categorical variables.
2. **Exploratory Data Analysis (EDA)**: Perform analysis on the dataset to understand variable distributions, detect outliers, and check for correlations between features.
3. **Model Building**: Train various classification models (e.g., Logistic Regression, Decision Trees, Random Forest, etc.) and evaluate their performance.
4. **Model Evaluation**: Evaluate models based on metrics such as accuracy, precision, recall, and F1 score. Use feature importance techniques to interpret key features influencing predictions.
5. **Recommendations**: Provide recommendations to the bank on critical factors to consider during the loan approval process based on model outputs.

