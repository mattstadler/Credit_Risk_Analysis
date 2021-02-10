# Credit_Risk_Analysis

## Overview
- The purpose of this project is to create machine learning models to predict credict default risk
- Analysis of each model can provide insight into which might work best

## Results
- The accuracy, precision & recall scores of detecting high risk loans are as follows

### Naive Random Oversampling
- Accuracy: 66%
- Precision: 1%
- Recall: 70%

### SMOTE Oversampling
- Accuracy: 62%
- Precision: 1%
- Recall: 57%

### Undersampling
- Accuracy: 65%
- Precision: 1%
- Recall: 66%

### Combination SMOTEENN
- Accuracy: 65%
- Precision: 1%
- Recall: 75%

### Balanced Random Forest
- Accuracy: 91%
- Precision: 4%
- Recall: 66%

### Easy Ensemble Classifier
- Accuracy: 94%
- Precision: 7%
- Recall: 92%

## Summary
- It is clear from the data that all models have relatively high accuracy and recall with low precision
- The easy ensemble classifier model has the highest accuracy, precision & recall and thus is recommended for use
