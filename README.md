# Logistic-Regression-and-k-Nearest-Neighbors-k-NN-Classification-with-Bank-Customer-Data

🎯 **Objective:** 

>The objective of this assignment is to gain practical experience with two popular classification algorithms: Logistic Regression and k-Nearest Neighbors (k-NN). You will apply these algorithms to predict customer churn using the BankChurners dataset and compare their performances.

**Tasks to Perform:**

**Part 1: Logistic Regression**
1. Data Exploration:

>Load the dataset and inspect the first few rows.

>Explore the distribution of the target variable Attrition_Flag (churn or not).

>Summarize the numerical features and identify any potential outliers or anomalies.

2. Data Preprocessing:
   
>Convert the Attrition_Flag column into a binary variable where 'Attrited Customer' is converted to 1 and 'Existing Customer' is converted to 0.

>Handle any missing values in the dataset, if present.

>Normalize or standardize the numerical features to ensure that they are on the same scale.

>Convert categorical variables into numerical values using one-hot encoding or label encoding.

>Split the data into training and testing sets with an 80-20 split.

4. Model Training:
   
>Implement a Logistic Regression model using Scikit-learn.

>Train the model on the training data.

6. Prediction:
>Use the trained Logistic Regression model to predict whether a new customer will churn based on provided feature values.

>Evaluate the confidence level of the prediction and discuss any potential limitations.

**Part 2: k-Nearest Neighbors (k-NN) Classification:**

1. Data Preprocessing:
   
>Reuse the preprocessed data from Part 1.

>Ensure that the data is normalized or standardized, as k-NN is sensitive to the scale of the data.

2. Model Training:
   
>Implement the k-NN classification algorithm using Scikit-learn.

>Experiment with different values of k (the number of neighbors) and find the optimal k by evaluating performance on the validation set.

3. Comparison with Logistic Regression:
   
>Compare the performance of your k-NN model with the Logistic Regression model you built in Part 1.

>Discuss the strengths and weaknesses of each approach.

4. Prediction:
   
>Use the trained k-NN model to predict whether a new customer will churn based on provided feature values.

>Evaluate the confidence level of the prediction and discuss any potential limitations.

5. Visualization:
   
>Create visualizations to represent the impact of different k values on model performance.

>Plot the decision boundary for the k-NN classifier if the dataset is reduced to two dimensions.
