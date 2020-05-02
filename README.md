# CSCI 5461 Project Proposal: Human Gene Function Prediction Challenge

Collaboraters: Shrijana Gurung and Jesus Garcia Garcia

# Dataset: Provided in Kaggle
Human genetic Interaction Profiles
GO Term Annotation matrix

# Approach:
To finalize our approach for this data challenge, we initially intend to explore multiple multi-classifiers on the given dataset. We will select the one with the best accuracy on the validation set as well as apply cross-validation on the training data set (similar to that of HW 2).

# Data Normalizations: Standardization method

# Possible Use of Feature Selection: 
Feature selection methods often enhance the ML performance. Hence, a correlation-based feature selection method will be attempted with the following learning algorithms to check for performance improvements.

# Learning Algorithms to attempt: 
Multi-Level Perceptron (ANN) 
K Nearest Neighbor (KNN): Choosing k as sqrt(N) where N is the total number of training data
Random forest classification algorithm

# Evaluation metrics to choose the final algorithm:
Prediction accuracy: Percent of correct classification on the validation data
Apply cross-validation on the training data set, Leave-p-out cross-validation (LPOCV)
