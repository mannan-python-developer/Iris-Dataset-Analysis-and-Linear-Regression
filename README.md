# Iris Dataset Analysis with Support Vector Classifier (SVC)

This Jupyter Notebook presents a Python script for analyzing the famous Iris dataset using the Scikit-Learn library, specifically employing the Support Vector Classifier (SVC). The dataset is loaded from a CSV file and preprocessed for machine learning.

## Data Preprocessing

The initial steps include importing the necessary libraries. The dataset is loaded and prepared by dropping the 'Id' column. The 'Species' column is encoded into numerical values (1, 2, and 3) representing the three different iris species.

## Data Splitting

The dataset is split into training and testing sets using the `train_test_split` function from Scikit-Learn. 70% of the data is used for training the Support Vector Classifier, and 30% is reserved for testing.

## Support Vector Classifier (SVC)

This notebook implements a Support Vector Classifier with a linear kernel using the `SVC` class from Scikit-Learn. The model is trained on the training data, and predictions are made on the test set.

## Model Evaluation

The performance of the Support Vector Classifier is evaluated using the accuracy score on the test set. The score indicates the proportion of correctly classified instances.

## Conclusion

The SVC model demonstrates perfect accuracy with a score of 1.0 on the Iris dataset. This notebook provides an alternative example of classification using the Support Vector Classifier.
