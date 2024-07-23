# Insurance Claim Prediction

## Project Description

This project involves predicting the likelihood of insurance claims using various machine learning models. The dataset includes features such as customer demographics, policy details, and incident information. The primary goal is to build and compare multiple models to determine which provides the best predictive performance.

The key steps in this project include:

1. Data Preprocessing: Cleaning and preparing the dataset for modeling.
2. Feature Engineering: Creating new features to enhance model performance.
3. Model Training: Using various machine learning algorithms to train models.
4. Model Evaluation: Comparing model performance using accuracy metrics.
5. Hyperparameter Tuning: Optimizing model parameters for better performance.

## Models Used

- **SVM (Support Vector Machine)**: A classification model that finds the hyperplane that best separates the data into different classes.
- **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies new cases based on a similarity measure.
- **Decision Tree Classifier**: A tree-based model that splits the data into subsets based on the most significant attributes.
- **AdaBoost**: An ensemble method that combines multiple weak classifiers to create a strong classifier.
- **Gradient Boosting**: An iterative method that combines weak learners to minimize the loss function.
- **Stochastic Gradient Boosting**: A variant of gradient boosting that uses a subsample of data to build each tree.
- **XGBoost**: An optimized implementation of gradient boosting that is efficient and scalable.
- **CatBoost**: A gradient boosting algorithm that handles categorical features effectively.
- **Extra Tree Classifier**: An ensemble method that uses random splits to build multiple trees.
- **Voting Classifier**: An ensemble method that combines the predictions of multiple models.

## Model Accuracy Results


| Model                        | Accuracy |
|------------------------------|----------|
| SVM Model (Training)         | 0.95     |
| SVM Model (Testing)          | 0.93     |
| K-Nearest Neighbors (Training) | 0.91   |
| K-Nearest Neighbors (Testing)  | 0.89   |
| Decision Tree (Training)       | 0.97   |
| Decision Tree (Testing)        | 0.85   |
| Random Forest (Training)       | 0.98   |
| Random Forest (Testing)        | 0.90   |
| AdaBoost (Training)            | 0.92   |
| AdaBoost (Testing)             | 0.88   |
| Gradient Boosting (Testing)    | 0.89   |
| Stochastic Gradient Boosting (Testing) | 0.87 |
| XGBoost (Training)             | 0.96   |
| XGBoost (Testing)              | 0.92   |
| CatBoost (Testing)             | 0.91   |
| Extra Tree Classifier (Testing) | 0.89   |
| Voting Classifier (Training)   | 0.97   |
| Voting Classifier (Testing)    | 0.93   |


