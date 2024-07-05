# House Price Prediction Using Various Regression Models

This repository contains code to predict house prices using various regression models. The project includes data preprocessing, feature selection, model training, evaluation, and visualization of results.

## Overview

This project uses a dataset of house prices to train and evaluate several regression models. The goal is to predict the sale price of houses based on various features.

## Dataset

The dataset used in this project is provided in the file `train.csv`.

## Installation

To run the code in this repository, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip.

## Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Run the Jupyter notebook.

## Project Steps

### 1. Data Loading

The dataset is loaded and the first few rows are displayed to understand its structure.

### 2. Data Preprocessing

This step handles missing values and encodes categorical variables. Missing values in numeric columns are replaced with the mean, while missing values in categorical columns are replaced with the most frequent value. Categorical variables are then encoded into numeric values.

### 3. Feature Selection

RandomForestRegressor is used for feature selection. This process helps in identifying the most important features that contribute to predicting house prices. The dataset is then transformed to keep only the selected features.

### 4. Train-Test Split

The data is split into training and testing sets to evaluate the performance of the models.

### 5. Standardize Features

The features are standardized for better model performance, ensuring that all features contribute equally to the model.

### 6. Model Training and Evaluation

Several regression models are trained and evaluated, including Linear Regression, Ridge Regression, Lasso Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Regressor. Each model is trained on the training data, and its performance is evaluated on the testing data. The evaluation metrics used are Mean Squared Error (MSE) and R2 Score.

### 7. Results Visualization

The R2 scores and MSE of the models are visualized using bar plots. This helps in comparing the performance of different models and selecting the best model for house price prediction.

## Conclusion

This project demonstrates the process of predicting house prices using various regression models. It includes data preprocessing, feature selection, model training, evaluation, and result visualization. The code and methodology can be adapted to similar regression problems.
