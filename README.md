# CODEALPHA__DiseasePrediction
Machine learning model to predict disease risk from patient medical data using  SVM, Random Forest and XGBoost — CodeAlpha ML Internship Task 4.
## About This Project

This project builds a Disease Prediction system that classifies whether 
a patient is at risk of a disease based on their medical data. It was 
developed as part of the CodeAlpha Machine Learning Internship (Task 4).

The system trains and compares four classification algorithms —Support Vector Machine (SVM), Random Forest, and XGBoost — 
on a structured medical dataset from the UCI Machine Learning Repository. 
The best performing model is saved and used to predict disease risk for 
new patients given their clinical values.

The project covers the complete ML pipeline from raw data to deployment-
ready prediction, including data cleaning, exploratory data analysis, 
feature scaling, model training, evaluation with multiple metrics, and 
a reusable predict_disease() function that takes patient data as input 
and returns a risk label with probability score.
