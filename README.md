## Diabetes-Readmission-Classifier

The objective of this exercise is to develop machine learnings models that will help hospitals reduce their readmission rates among diabetic patients.

## Motivation

In an effort to improve the quality of hospital care in the United States, the Affordable Care Act created the Hospital Readmission Reduction Program to improve the quality of healthcare for Americans by tying hospital payments to patient readmission rates. In other words, this program seeks to incentivize hospitals to provide high quality healthcare by financially penalizing hospitals with higher readmission rates.

This project endeavors to aid in achieving the goals set forth by the Hospital Readmission Reduction Program by positively impacting two key stakeholders in the American healthcare system:

- Patients: Correctly identifying patients who are likely to be readmitted and will enable hospitals to take preventative measures so that patients will receive the best possible healthcare and avoid adverse health consequences
- Hospitals: Tying lower readmission rates to higher hospital revenues will foster efficiency from a financial perspective, allowing hospitals to reallocate a larger pool of resources to important expenses such as personal protective equipment
In short, lower readmission rates lead to better health for patients and better fiscal health for hospitals.

## Process

1. Data Processing
2. Training Base Machine Learning Algorithms
3. Evaluating Base Machine Learning Algorithms (AUC / Feature Importance)
4. Hyperparameter Tuning with GridSearchCV + Other Machine Learning Techniques (Bagging / Stacking)
5. Evaluating Optimized Machine Learning Algorithms (AUC / Feature Importance)

## Result 

After evaluating the machine learning models that we have trained in this project, we were able to achieve a maximum AUC of 0.63 with the following models:

- Logistic Regression Classifier
- Tuned Logistic Regression Classifier
- Bagged Logistic Regression Classifier
- Tuned Random Forest Classifier
- Stacked Classifier

## Requirements

- pandas
- numpy 
- matplotlib 
- seaborn 
- imblearn 
- sklearn 
- xgboost

