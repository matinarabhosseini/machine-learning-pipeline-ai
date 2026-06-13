# Machine Learning Pipeline AI

This repository contains an Artificial Intelligence course assignment focused on building and evaluating machine learning models for classification and regression tasks.

The project covers the full machine learning workflow, including preprocessing, feature engineering, model training, evaluation, prediction generation, and model comparison.

## Overview

The assignment is based on a fictional AI service called **Match-UT**, designed to predict different student-related academic and behavioral outcomes using machine learning techniques.

The project includes multiple supervised learning tasks such as binary classification, multi-class classification, and regression.

## Main Topics

- Decision Tree implementation and analysis
- Naive Bayes classification
- Text classification
- Multi-class classification
- Ensemble learning
- Random Forest
- Boosting methods
- XGBoost
- Regression modeling
- Bias-Variance analysis
- Model evaluation

## Assignment Parts

### Part 1 — Project Completion Prediction

A binary classification task that predicts whether a group project will be completed on time.

This part includes:

- Decision Tree implementation from scratch
- Entropy/Gini-based splitting
- Tree depth control
- Feature engineering
- Validation-based evaluation

### Part 2 — Email Importance Classification

A text classification task that classifies emails as important or spam.

This part includes:

- Text preprocessing
- Bag-of-Words representation
- Binary and count-based vectorization
- Naive Bayes classification
- Decision Tree comparison

### Part 3 — Student Crisis Type Prediction

A multi-class classification task that predicts the type of student crisis before an exam.

This part includes:

- Data preprocessing
- Missing value handling
- Outlier management
- Categorical encoding
- Feature engineering
- Decision Tree classification
- Random Forest
- Bagging
- Boosting models
- One-vs-Rest classification

### Part 4 — Final Exam Score Prediction

A regression task that predicts the final exam score of students.

This part includes:

- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- MSE calculation
- MAE calculation
- R² Score calculation
- Bias-Variance analysis

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-Learn
- XGBoost
- Matplotlib
- Machine Learning
- Data Analysis

## Repository Structure

```text
.
├── CA3.ipynb
├── AI_CA3.pdf
├── part2_dataset.csv
├── part2_test.csv
├── part2_test_predictions_binary_nb.csv
├── part2_test_predictions_count_nb.csv
├── part3_dataset.csv
├── part3_test.csv
├── part3_test_predictions.csv
├── part4_dataset.csv
├── part4_test.csv
├── part4_test_predictions_RandomForestRegressor.csv
├── s1_part1_dataset.csv
├── s1_part1_test.csv
├── s1_part2_dataset.csv
├── s1_part2_test.csv
├── s1_part2_test_predictions.csv
├── s1_part2_test_predictions_binary_nb.csv
├── s1_part2_test_predictions_count_nb.csv
└── README.md
```

## Files

- `CA3.ipynb` contains the main implementation.
- `AI_CA3.pdf` contains the original assignment description.
- Dataset files contain the training and test data used in different parts.
- Prediction files contain generated outputs for the assignment test sets.

## Evaluation Metrics

The project uses different evaluation metrics depending on the task type.

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Multi-Class Classification

- Overall Accuracy
- Macro Precision
- Macro Recall
- Macro F1 Score
- Multi-class Confusion Matrix

### Regression

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

## Key Learning Outcomes

This project helped practice:

- Building machine learning workflows
- Implementing decision trees from scratch
- Comparing classical ML models
- Handling categorical and numerical data
- Performing feature engineering
- Evaluating classification and regression models
- Understanding ensemble learning methods
- Studying bias-variance behavior experimentally

## Academic Context

This project was developed as part of an Artificial Intelligence course assignment at the University of Tehran.

It is organized here for academic documentation and portfolio presentation.
