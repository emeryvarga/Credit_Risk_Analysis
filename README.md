# Credit_Risk_Analysis

## Overview
The purpose of this analysis is apply machine learning to predict credit card risk for Fast Lending, a peer lending services company.

## Results

### Naive Random Oversampling
* Accuracy Score: 0.65
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .61/.68

### Smote Oversampling
* Accuracy Score: 0.62
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .61/.64
* 
### Undersampling
* Accuracy Score: 0.62
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .61/.43

### Combination Under-Over Sampling
* Accuracy Score: 0.52
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .70/.58

### Balanced Random Forest Classifier
* Accuracy Score: 0.79 
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .91/.94

### Easy Ensemble AdaBoost Classifier
* Accuracy Score: 0.93
* Precision: low for High-risk loans and high for Low-risk loans
* Recall: High/Low risk = .91/.94


## Summary
The Easy Ensemble AdaBoost Classifier is the best model to apply for credit card risk with a 0.93 balanced accuracy. Out of the six models, this accuracy score is closest to 1.
