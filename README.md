# Credit Risk Analysis Report
## Overview of the analysis:
The purpose of this analysis is to determine the best machine learning model for predicting credit risk among various oversampling, undersampling, combination sampling, and ensemble learning techniques. By analyzing the performance of these models, we can provide recommendations on which model to use for predicting credit risk.

## Results:
Balanced accuracy scores and precision and recall scores for the six machine learning models are as follows:

### Naive Random Oversampling:

- Balanced Accuracy Score: 0.6547
- Precision: High Risk - 0.01, Low Risk - 1.00
- Recall: High Risk - 0.72, Low Risk - 0.59

### SMOTE Oversampling:

- Balanced Accuracy Score: 0.6620
- Precision: High Risk - 0.01, Low Risk - 1.00
- Recall: High Risk - 0.63, Low Risk - 0.69

### Cluster Centroids Undersampling:

- Balanced Accuracy Score: 0.5442
- Precision: High Risk - 0.01, Low Risk - 1.00
- Recall: High Risk - 0.69, Low Risk - 0.40

### SMOTEENN Combination Sampling:

- Balanced Accuracy Score: 0.6473
- Precision: High Risk - 0.01, Low Risk - 1.00
- Recall: High Risk - 0.72, Low Risk - 0.57

### Balanced Random Forest Classifier (Ensemble):

- Balanced Accuracy Score: 0.7885
- Precision: High Risk - 0.03, Low Risk - 1.00
- Recall: High Risk - 0.70, Low Risk - 0.87


### Easy Ensemble AdaBoost Classifier (Ensemble):

- Balanced Accuracy Score: 0.9316
- Precision: High Risk - 0.09, Low Risk - 1.00
- Recall: High Risk - 0.92, Low Risk - 0.94


## Summary:
Based on the results, the Easy Ensemble AdaBoost Classifier model outperforms the other models with a balanced accuracy score of 0.9316, the highest precision and recall scores for high risk and low risk loans. Therefore, we recommend using the Easy Ensemble AdaBoost Classifier model for credit risk prediction. While the other models show some potential, they are not as effective as the Easy Ensemble AdaBoost Classifier in terms of accuracy, precision, and recall. Consequently, I do not recommend using those models for this specific purpose.
