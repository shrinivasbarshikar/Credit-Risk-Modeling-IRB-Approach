Credit Risk Modeling and Scorecard Development using the IRB Approach


Overview
This project focuses on building credit scores and calculating credit risk for financial institutions using the Internal Ratings-Based (IRB) Approach. The goal is to model Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD), which are critical components of credit risk assessment. These models can help banks estimate potential losses and optimize their capital requirements.

Key Features
Credit Scoring: Develop a scorecard based on customer financial history, demographics, and other data to predict creditworthiness.
Risk Estimation: Use advanced statistical techniques and machine learning algorithms to estimate PD, LGD, and EAD.
IRB Approach: Implement the IRB framework, which allows banks to use their internal models for assessing credit risk and calculating regulatory capital.
Loss Calculation: Estimate potential losses for banks based on risk parameters and stress testing.
Data Integration: Process various datasets, including financial statements, credit reports, and transaction history.
Methodology
Data Preprocessing:

Clean and preprocess customer data, transaction histories, and credit bureau information.
Feature engineering to extract relevant risk indicators.
Modeling Credit Risk:

PD Modeling: Build a logistic regression or machine learning model to estimate the probability that a borrower will default on their loan.
LGD Modeling: Estimate loss given default using regression models based on historical recovery rates.
EAD Modeling: Use exposure at default to determine how much the bank stands to lose at the time of default.
IRB Framework:

Foundation IRB: Use predefined risk factors for PD, LGD, and EAD.
Advanced IRB: Allow the use of internal models to calculate PD, LGD, and EAD for capital requirements.
Backtesting and Validation:

Assess the model performance using cross-validation, ROC curves, and accuracy metrics.
Perform stress testing to evaluate model robustness in different economic scenarios.
Tech Stack
Python: For data analysis, modeling, and backend.
Pandas, NumPy: Data manipulation and preprocessing.
Scikit-learn, Logistic Regression: For building machine learning models.
scorecardpy:Visualisation of WOE (Weight of Evidence)
