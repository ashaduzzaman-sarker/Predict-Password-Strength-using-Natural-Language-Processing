
# Predict Password Strength using Natural Language Processing

This repository contains a machine learning project that predicts the strength of passwords using natural language processing techniques. The project includes data preprocessing, feature engineering, model training, evaluation, and deployment steps.

## Overview

In this project, we aim to predict the strength of passwords based on various features such as length, character frequencies, and TF-IDF scores. We utilize machine learning algorithms, particularly logistic regression, to classify passwords into weak, medium, or strong categories. The project also provides an interactive interface for users to check the strength of their passwords.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/ashaduzzaman-sarker/Predict-Password-Strength-using-Natural-Language-Processing.git
```

2. Install the required dependencies:

'''
pip install -r requirements.txt
'''
  
3. Open the Jupyter Notebook `Predict Password Strength using Natural Language Processing.ipynb` to explore the project.

## Usage

Follow the instructions provided in the Jupyter Notebook to understand the project workflow, including data preprocessing, feature engineering, model training, evaluation, and prediction.

## Features

  The project includes the following features:

- Data Preprocessing: Removing irrelevant features, checking for duplicate rows, handling missing values, and exploring data types.
- Semantic Analysis: Analyzing password characteristics such as numeric, uppercase, lowercase, alphabetic, alphanumeric, title-case, and special characters.
- Feature Engineering: Creating features based on password length and character frequencies.
- Descriptive Statistics: Analyzing the relationship between features and password strength using statistical measures and visualizations.
- TF-IDF Transformation: Converting password data into numerical form using TF-IDF vectorization.
- Machine Learning Algorithm: Training a logistic regression model to predict password strength.
- Model Evaluation: Assessing the accuracy of the model using confusion matrix, classification report, and accuracy score.
- Interactive Interface: Providing a function to predict the strength of user-entered passwords.

## Results

- Accuracy Score: The model achieved an accuracy score of `100%` on the test set.
- Confusion Matrix: The confusion matrix provides insights into the performance of the model across different strength categories.
- Classification Report: The classification report presents precision, recall, F1-score, and support for each strength category.

## Contributors
```
Ashaduzzaman Sarker
https://github.com/ashaduzzaman-sarker
```

Contributions to this project are welcome! If you have any ideas for improvement, bug fixes, or new features, feel free to open an issue or submit a pull request.


