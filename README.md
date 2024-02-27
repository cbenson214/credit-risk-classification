# credit-risk-classification
Credit Risk Analysis Report

Overview
The purpose of this analysis is to train and evaluate a model to predict loan risk based on historical lending activity from a peer-to-peer lending service company. If the model is accurate, it could provide the lender with a creditworthiness label for its borrowers.

Results
•	Accuracy Score: 99.52%
•	Precision Score: 
o	Healthy Loan Prediction:	100%
o	High-Risk Loan Prediction:	87%
•	Recall Score:
o	Health Loan Prediction:		100%
o	High-Risk Loan Prediction:	100%

Summary
The model’s 99.52% Accuracy makes it a very solid tool for the lender and solidifies my recommendation for using it. With 100% scores in Recall and Healthy Loan Precision, the model is consistent and reliable. The model doesn’t suffer from only scoring 87% in High-Risk Prediction Precision because High-Risk Loans only make up 3.3% of the total data set and therefore don’t significantly alter the effectiveness of the model. 


All code written by Christopher Benson. Reference for imbalanced-learn's over-sampling found at <https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html>.
Code can be found at credit_risk_classification.ipynb located in the Credit_Risk directory.