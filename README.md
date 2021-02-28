# Credit Risk Analysis: Which Model is Right for the Job?

## Overview

### Introduction

The world of machine learning offers a wide variety of models that make predictions on your dataset to varying degrees of accuracy (degrees of precision and recall as well). To test which one is the best for assessing risk in the field of credit, six supervised machine learning models were trained on the same data set and the results of their performance were stored in confusion matrices and classification reports. The six models in question are: Naive Random Oversampling, SMOTE Oversampling,  Cluster Centroids Undersampling, SMOTEENN combination Over and Undersampling, Balanced Random Forest Classifier, Easy Ensemble AdaBoost Classifier.

### Resources

This analysis employs the pandas, scikit-learn, and imbalanced-learn python libraries to both parse and model the results seen below

## Results

The results here will highlight each model's performance when it comes to accurately predicting high risk clients, as avoiding high risk loans will save the business more money.

### Naive Random Oversampling

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 65%
* Precision: 1%
* Recall: 74%

### SMOTE Oversampling

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 66%
* Precision: 1%
* Recall: 63%

### Cluster Centroids Undersampling

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 54%
* Precision: 1%
* Recall: 69%

### SMOTEENN Combination Over/Undersampling

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 64%
* Precision: 1%
* Recall: 70%


### Balanced Random Forest Classifier, Easy Ensemble AdaBoost Classifier

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 79%
* Precision: 3%
* Recall: 70%

### Easy Ensemble AdaBoost Classifier

![INSERT PICTURE HERE]
![INSERT PICTURE HERE]

Key Metrics:
* Balanced Accuracy: 93%
* Precision: 9%
* Recall: 92%

## Summary

### Performance Evaluation

The model that performed the best out of this selection was the Easy Ensemble AdaBoost Classifier with 9% precision. Prioritizing precision in this decision is important because incorrectly identifying a client as high-risk results in a loss of potential business.

### Recommendation

 It is recommended that the business look for alternative machine learning models to help in the decision making process. In the best case scenario, Adaboost correctly guesses a high risk client approximately 9/100 times, the other 91 times would result in rejected clients that would have been likely to repay their loans.