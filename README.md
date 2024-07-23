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

| Model                        | Accuracy                  |
|------------------------------|---------------------------|
| SVM Model (Training)         | svc_model.predict(X_train)) |
| SVM Model (Testing)          | y_pred)                    |
| K-Nearest Neighbors (Training) | knn_model.predict(X_train)) |
| K-Nearest Neighbors (Testing)  | y_pred)                    |
| Decision Tree (Training)       | decision_tree_model.predict(X_train)) |
| Decision Tree (Testing)        | y_pred)                    |
| Random Forest (Training)       | rf_model.predict(X_train)) |
| Random Forest (Testing)        | y_pred)                    |
| AdaBoost (Training)            | ada_model.predict(X_train)) |
| AdaBoost (Testing)             | y_pred)                    |
| Gradient Boosting (Testing)    | gb.predict(X_test))       |
| Stochastic Gradient Boosting (Testing) | sgb.predict(X_test))     |
| XGBoost (Training)             | xgb.predict(X_train))     |
| XGBoost (Testing)              | y_pred)                    |
| CatBoost (Testing)             | cat.predict(X_test))      |
| Extra Tree Classifier (Testing) | etc.predict(X_test))      |
| Voting Classifier (Training)   | vc.predict(X_train))      |
| Voting Classifier (Testing)    | y_pred)                    |

