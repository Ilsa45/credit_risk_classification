# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

Purpose:
The purpose of this analysis was to build and evaluate a machine learning model capable of predicting loan status based on financial information. The model was used to classify loans as either healthy loans or high risk loans.
Data Overview:
The dataset used for this model contains information including:
	•	Loan size
	•	Interest rate
	•	Borrower income
	•	Debt-to-income ratio
	•	Number of accounts
	•	Derogatory marks
	•	Total debt
The target variable being loan status ;0 = healthy loan, 1 = high risk loan

The stages of machine learning processes used can be seen below:
1. Data loading & processing
2. Data preparation
3. Model training
4. Model Prediction
5. Model Evaluation
   

* Method:
* In this model, Logistic Regression was used to predict the outcome. This is an efficient algo when handling features and target variables.

## Results

* Machine Learning Model 1:
    •	Accuracy: 99%
	•	Precision:
	•	Class 0 (Healthy Loans): 100% 
	•	Class 1 (High-Risk Loans): 84% 
	•	Recall:
	•	Class 0: 99% 
	•	Class 1: 94% 

## Summary

The Logistic Regression model performed best with 99% accuracy, 94% recall for high-risk loans, and 84% precision. This ensures that most high-risk loans are correctly identified, minimizing false negatives.

Since financial risk assessment prioritizes recall (catching high-risk loans), Logistic Regression is the recommended model for its efficiency and strong predictive ability.
