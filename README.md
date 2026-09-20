
# Financial-Loan-Risk-ML

## Project Overview

This project analyses a financial loan dataset to understand borrower and loan characteristics associated with different loan repayment outcomes and to develop machine learning classification models for predicting loan status.

The project is completed as part of an AI-assisted Machine Learning group assignment.

## Problem Statement

The study aims to analyse borrower and loan-related characteristics and use machine learning classification techniques to predict loan repayment status, thereby supporting data-driven loan risk assessment.

## Domain

**Finance — Credit and Loan Risk Analytics**

## Dataset

The dataset contains borrower and loan-related information such as:

* Employment length
* Home ownership
* State
* Annual income
* Debt-to-income ratio
* Loan amount
* Installment
* Interest rate
* Loan term
* Loan purpose
* Credit sub-grade
* Verification status
* Total credit accounts
* Loan status

### Target Variable

**Loan_Status**

The target contains the following categories:

* Fully Paid
* Current
* Charged Off

Therefore, the primary machine learning problem is a **multiclass classification problem**.

## Dataset Source

**Dataset:** Financial Loan Dataset

The dataset source, usage conditions, and relevant limitations should be verified before redistribution.

## Project Workflow

The project follows the following analytical workflow:

1. Problem identification
2. Dataset understanding
3. Data authenticity assessment
4. Variable classification
5. Descriptive statistics
6. Frequency distribution analysis
7. Exploratory Data Analysis (EDA)
8. Missing-value and duplicate checks
9. Outlier analysis
10. Feature engineering
11. Categorical variable encoding
12. Train-test splitting
13. Feature scaling
14. Machine learning model development
15. Model evaluation
16. Class-imbalance analysis
17. Cross-validation
18. Hyperparameter tuning
19. Feature importance analysis
20. Interpretation and financial implications

## Machine Learning Models

The project evaluates multiple classification algorithms:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost
* XGBoost

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC, where applicable
* Cross-validation performance

Because the loan-status classes are imbalanced, model assessment does not rely on accuracy alone.

## Data Preprocessing

The preprocessing stage includes:

* Duplicate checking
* Missing-value checking
* Outlier analysis
* Date transformation
* Financial feature engineering
* Categorical encoding
* Numerical feature scaling
* Class-imbalance handling where appropriate

## Feature Engineering

Additional financially meaningful variables are created where justified, including:

* Loan-to-Income Ratio
* Annual Installment-to-Income Ratio
* Issue Year
* Issue Month
* Issue Quarter

## Key Project Questions

The analysis focuses on questions such as:

* What are the characteristics of borrowers in the dataset?
* How are loan outcomes distributed?
* How do income, DTI, interest rate and loan amount differ across loan-status categories?
* Which categorical factors are associated with different loan outcomes?
* Can machine learning classify loan repayment status?
* How do different classification algorithms compare?
* Which features contribute most to model predictions?
* What are the practical implications for loan risk assessment?

## Academic Context

This project was developed for an academic Machine Learning group assignment. The analysis demonstrates the application of EDA, data preprocessing, classification algorithms, model evaluation, model comparison and interpretation.

## Limitations

The findings should be interpreted within the limitations of the available dataset. In particular:

* The dataset represents historical loan observations and may not represent all borrowers or lending environments.
* Observed relationships should not automatically be interpreted as causal relationships.
* Class imbalance can affect minority-class prediction performance.
* Model performance may change when applied to a different population or time period.
* Feature importance indicates predictive contribution within the model and should not automatically be interpreted as causal influence.
