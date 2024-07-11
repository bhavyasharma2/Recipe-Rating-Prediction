# Recipe Rating Prediction

## Overview

This project was undertaken as a capstone project for the Machine Learning Practices (MLP) course at IIT Madras. The objective of this Kaggle competition is to predict the ratings of various recipes based on a given dataset containing recipe names, reviews, and other relevant details.

## Description

The challenge revolved around predicting the rating of food recipes. Participants were provided with a comprehensive dataset comprising recipe names, reviews, and various relevant features. The goal was to build models that could accurately predict the ratings for each recipe using the provided information. Submissions were evaluated based on their accuracy score.

## Notebook Content

The Jupyter Notebook includes the following sections:

### Data Loading and Exploration

- Loaded training and test datasets using Pandas.
- Displayed the first few rows of the datasets to understand the structure.
- Checked the shape and summary statistics of the training dataset.
- Examined the number of unique values and listed them for each column.
- Segregated numerical and categorical columns for further analysis.

### Data Visualization

- Visualized the distribution of ratings.
- Plotted correlations among numerical features.
- Generated count plots for categorical features.
- Created box plots and histograms to understand the distribution of data.

### Data Preprocessing

- Handled missing values using SimpleImputer.
- Encoded categorical variables using one-hot encoding.
- Scaled numerical features using StandardScaler.

### Model Building and Evaluation

Built and evaluated several machine learning models:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **K-Nearest Neighbors Classifier**
4. **Decision Tree Classifier**
5. **LightGBM Classifier**
6. **XGBoost Classifier**

For each model:
- Hyperparameter tuning was performed using GridSearchCV.
- Models were evaluated using accuracy, precision, recall, and F1-score.

### Model Evaluation

- Displayed confusion matrices for each model to visualize prediction performance.
- Selected the best model based on evaluation metrics.

### Submission

- Predicted ratings on the test set using the best model.
- Prepared a submission file in the required format for Kaggle.

## Results

- Achieved an accuracy score of **78.14%** on the test set.
- The model shows promising results in predicting recipe ratings based on the given features.

## Acknowledgements

- Special thanks to IIT Madras for the opportunity to work on this project.
- Thanks to the Kaggle community for providing a platform to showcase and enhance our machine learning skills.
