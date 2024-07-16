# Email Spam Classification

This repository demonstrates hyperparameter tuning for email spam classification using GridSearchCV and RandomizedSearchCV with multiple machine learning models in Scikit-Learn.

## Project Overview

The aim of this project is to classify emails as spam or not spam using various machine learning models. Hyperparameter tuning is performed to optimize model performance.

## Models Used

- Logistic Regression
- Naive Bayes
- Support Vector Machines (SVM)
- Random Forest
- Gradient Boosting

## Hyperparameter Tuning

### GridSearchCV

GridSearchCV is used to perform an exhaustive search over a specified parameter grid. It evaluates all possible combinations of hyperparameters to find the best model.

### RandomizedSearchCV

RandomizedSearchCV performs a random search over specified parameter values. It is more efficient than GridSearchCV for large datasets or when there are many hyperparameters to tune.

## Dataset

The dataset used for this project consists of labeled emails, categorized as spam or not spam.
