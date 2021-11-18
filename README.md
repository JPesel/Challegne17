# Challenge 17

## Overview
For this challenge we went over a data set for credit risks and we used machine learning to predict which users are more likely to get accepted.

## Results
Random Oversampling:
  - Balanced Accuracy Score: 64.5%. 
  - High Risk Precision:0.01
  - High Risk Recall: 0.61
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.68

SMOTE Oversampling:
  - Balanced Accuracy Score: 62.9%. 
  - High Risk Precision:0.01
  - High Risk Recall: 0.63
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.63

Cluster Centroid Undersampling:
  - Balanced Accuracy Score: 52.0%. 
  - High Risk Precision:0.01
  - High Risk Recall: 0.60
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.44

MOTEENN Combination (Over and Under) Sampling:
  - Balanced Accuracy Score: 63.9%. 
  - High Risk Precision:0.01
  - High Risk Recall: 0.69
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.59

Balanced Random Forest Classifier:
  - Balanced Accuracy Score: 73.4%. 
  - High Risk Precision:0.02
  - High Risk Recall: 0.60
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.87

Easy Ensemble AdaBoost Classifier: 
  - Balanced Accuracy Score: 92.6%. 
  - High Risk Precision:0.08
  - High Risk Recall: 0.91
  - Low Risk Precision: 1.00
  - Low Risk Recall: 0.94


## Summary
By the metrics we got we can see that the AdaBoost Classifier is the best for this ckind of problem, out matching the next one on the list 92% to 73%
