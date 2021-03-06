# RUTGERS - Credit Card Analysis

## Overview of the loan prediction risk analysis
For this challenge, we have been asked to create a machine learning model to help determine credit card risk. While using the credit card credit dataset from LendingClub and the imbalanced-learn and scikit-learn libraries, we will:

  1. Build and evaluate models using resampling.
  2. Oversample the data using the RandomOverSampler and SMOTE alrogithms and undersample using the ClusterCentroids algorithms.
  3. Use a combinatorial approach using the SMOTEENN algorithm.
  4. Compare the machine learning models that reduce bias and predict credit risk.

## Result
### Naive Random Oversampling
  - Balanced Accuracy Score: 0.6471540342692306 (65%)
  - High/Low Precision: 0.01 (1%) and 1.00 (100%)
  - High/Low Recall: 0.62 (62%) and 0.67 (67%)
  
 ### Random Undersampling
  - Balanced Accuracy Score: 0.6251596424010217 (63%)
  - High/Low Precision: 0.01 (1%) and 1.00 (100%)
  - High/Low Recall: 0.62 (62%) and 0.63 (63%)


### Comination (Over and Under) Sampling
  - Balanced Accuracy Score: 0.509315662883595 (63%)
  - High/Low Precision: 0.01 (1%) and 1.00 (100%)
  - High/Low Recall: 0.57 (57%) and 0.44 (44%)
  
### Random Forest
  - Balanced Accuracy Score: 0.67209249388625 (67%)
  - High/Low Precision: 0.73 (73%) and 1.00 (100%)
  - High/Low Recall: 0.34 (34%) and 1.00 (100%)

### Easy Ensemble
  - Balanced Accuracy Score: 0.67209249388625 (67%)
  - High/Low Precision: 0.73 (73%) and 1.00 (100%)
  - High/Low Recall: 0.34 (34%) and 1.00 (100%)
