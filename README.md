# Boston Housing Price Prediction

This repository contains code for predicting median housing prices in Boston using various regression models including Linear Regression, Random Forest Regression, and Neural Network Regression.

## Purpose
The purpose of this project is to demonstrate how different regression models can be implemented and compared for the task of predicting median housing prices based on various features such as crime rate, average number of rooms, pupil-teacher ratio, etc. The goal is to determine which model performs best and gain insights into the most relevant features for predicting housing prices.

## How it Works
1. **Loading Data**: The data is loaded from the `housing.csv` file containing information about different features and median housing prices.
2. **Preprocessing Data**: The data is preprocessed by normalizing features using MinMaxScaler.
3. **Visualizing Data**: Correlation matrix and histogram of median housing prices are plotted to understand the relationships between features and the target variable.
4. **Train/Test Split**: The dataset is split into training and testing sets for model evaluation.
5. **Model Building**: Three regression models are implemented:
   - Linear Regression
   - Random Forest Regression
   - Neural Network Regression
6. **Model Evaluation**: Performance metrics including Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) are calculated for each model.
7. **Results and Discussion**: Results of each model are compared and discussed, and insights into important features for predicting housing prices are provided based on correlation analysis.

## Files
- `housing.csv`: Dataset containing information about housing features and median housing prices.
- `house_price_pred.ipynb`: Python script containing the code for loading data, preprocessing, model building, evaluation, and visualization.
- `readme.md`: Markdown file containing information about the project, how it works, and its components.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- torch (PyTorch)

  ### By Bhunakit Chantaraseno 6438143021
