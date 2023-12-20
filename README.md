# Credit-Analysis-Using-Machine-Learning-Techniques

## Introduction

This project is aimed at predicting loan status using machine learning techniques. The analysis is based on a dataset of credit risk containing 32581 samples.

## Objectives

- Preprocess the dataset to fit machine learning models.
- Utilize models like Random Forest, Gradient Boosting for prediction.
- Tune the hyperparameters using GridSearchCV.
- Evaluate model performance and identify default loan status and non-default loan status.

## Data Source

The dataset includes diagnostic measurements for diabetes from the `credit_risk_dataset.csv` dataset. It consists of various features such as 
- person_age: Age
- person_income: Annual Income
- person_home_ownership: Home ownership
- person_emp_length: Employment length (in years)
- loan_intent: Loan intent
- loan_grade: Loan grade
- loan_amnt:	Loan amount
- loan_int_rate:	Interest rate
- loan_status:	Loan status (0 is non-default，1 is default)
- loan_percent_income:	Percent income
- cb_person_default_on_file: Historical default
- cb_preson_cred_hist_length: Credit history length

## Tools and Technologies Used

- Python, Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, sklearn

## Results

The project successfully identifies 3 most effective predictors of credit risk (loan_percent_income, loan_int_rate, person_income), evaluates the accuracy of different machine learning models (the prediction accuracy rate reaches to 88%).
