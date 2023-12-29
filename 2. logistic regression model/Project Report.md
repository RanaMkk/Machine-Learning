# Project Report

## Title: Logistic Regression for University Admissions Prediction

### Executive Summary

In this project, we implemented logistic regression from scratch using only NumPy to predict university admissions based on exam scores. The dataset, obtained from "acceptance_data.txt," includes applicants' scores on two exams and the admissions decision.

### 1. Dataset Analysis

- Loaded dataset using NumPy.
- Examined the structure of the data (features and labels).
- Identified potential challenges (missing data, categorical features).

### 2. Data Preprocessing

- Handled missing data by replacing it with the mean.
- Applied Z-Score Normalization for feature scaling.
- Conducted log-scale transformation to address skewed data.
- Added a constant column for the bias term.

### 3. Train-Test Split

- Split the dataset into training and testing sets.
- Chose an 80-20 split ratio for training and testing, respectively.

### 4. Logistic Regression Implementation

- Defined the sigmoid function for logistic regression.
- Implemented the cost function and gradient descent algorithm.
- Initialized parameters and set hyperparameters (learning rate, iterations).
- Trained the logistic regression model on the training set.

### 5. Model Evaluation

- Made predictions on the test set using the trained model.
- Calculated accuracy to assess the model's performance on unseen data.

### 6. Future Predictions

- Discussed the process for generating predictions on new data.
- Emphasized the need for preprocessing new data in a similar manner.

### Conclusion

In conclusion, the logistic regression model successfully predicted university admissions based on exam scores. The implementation covered data analysis, preprocessing, model training, evaluation, and considerations for future predictions.
