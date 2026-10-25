# SC5002 Lab Assignment Part 2: Low-Code Machine Learning

## Description
This project uses the California Housing dataset to compare Linear Regression and Ridge Regression models. The aim is to evaluate their performance using 5-fold cross-validation and visualize the results.

## Requirements
The project uses the following Python libraries:
- NumPy
- pandas
- Matplotlib
- scikit-learn

The code is designed to run in Google Colab.

## Tasks

### Task 2.1: Dataset Setup
- Load the California Housing dataset from scikit-learn.
- Randomly select 1,000 records.
- Separate the features from the target variable (`MedHouseVal`).
- Standardize the features using `StandardScaler`.

### Task 2.2: Model Training and Cross-Validation
- Train a Linear Regression model and evaluate it using 5-fold cross-validation.
- Train three Ridge Regression models with alpha values of 0.1, 10, and 1000.
- Calculate the mean R² score for each model to compare their performance.

### Task 2.3: Visualization
Generate a bar chart comparing the mean 5-fold cross-validation R² scores of the four models. The chart displays each model's score to make performance comparisons easier.

## Output
The code produces:
- The first five rows of the sampled dataset.
- Mean 5-fold cross-validation R² scores for Linear Regression and each Ridge Regression model.
- A bar chart comparing the performance of all four models.

## Evaluation Metric
The models are evaluated using the R² score, which measures how well a model explains variation in the target variable. A higher R² score generally indicates better model performance.

