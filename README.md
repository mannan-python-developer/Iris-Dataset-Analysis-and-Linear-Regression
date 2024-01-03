# Iris Dataset Analysis and Linear Regression

This Jupyter Notebook contains a Python script for analyzing the famous Iris dataset using the Pandas and Scikit-Learn libraries. The dataset is loaded from a CSV file and preprocessed to prepare it for machine learning.

## Data Preprocessing

The initial steps include importing the necessary libraries, loading the dataset, and dropping the 'Id' column. The 'Species' column is then encoded into numerical values (1, 2, and 3) for the three different iris species.

## Data Splitting

The dataset is split into training and testing sets using the `train_test_split` function from Scikit-Learn. 70% of the data is used for training the linear regression model, and 30% is reserved for testing.

## Linear Regression Model

A linear regression model is implemented using the `LinearRegression` class from Scikit-Learn. The model is trained on the training data, and predictions are made on the test set.

## Model Evaluation

The performance of the linear regression model is evaluated using the R-squared score on the test set. The score indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Conclusion

The linear regression model shows a high R-squared score of 0.93, suggesting a good fit for the Iris dataset. This notebook provides a simple yet effective example of linear regression applied to real-world data.

*Note: Include any additional information or insights gained from the analysis as needed.*
