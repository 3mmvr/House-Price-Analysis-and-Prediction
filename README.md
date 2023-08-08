# Melbourne House Price Analysis & Prediction

This data science project involves analyzing and predicting house prices in Melbourne. The project is structured as follows:

## Overview

The primary goal of this project is to analyze and predict house prices in Melbourne, utilizing data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling techniques.

## Purpose and Impact

The project aimed to provide insights into the factors influencing house prices in Melbourne and to create a predictive model that accurately estimates house prices based on various features. This information can be valuable for real estate professionals, buyers, and sellers in making informed decisions. By utilizing advanced techniques such as Random Forest regression, the project enhances the accuracy of price predictions and offers a practical solution for understanding and forecasting the Melbourne housing market.

## Project Structure

1. **Introduction**: Initial data loading, setting up the environment, and examining the dataset's columns.
2. **Data Cleaning**:
   - Renaming columns for consistency and clarity.
   - Dealing with missing values, using mean imputation for numerical columns.
   - Replacing missing Council Area and Region Name based on postcode information.
   - Removing rows with specific Suburb values lacking matching Council Areas or Region Names.
   - Normalizing data types and addressing outliers in the YearBuilt and BuildingArea columns.
   - Converting categorical columns into numerical using one-hot encoding.

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing the distribution of house prices, the relationship between various features, and identifying outliers.
   - Analyzing the distribution of house types, car parking spaces, and other key features.
   - Exploring correlations between numeric features and the target variable (Price).

4. **Modeling**:
   - Implementing predictive models including Ridge, Lasso, Bayesian Ridge, ElasticNet, Random Forest, and Linear Regression.
   - Evaluating model performance using metrics such as Mean Squared Error (MSE), Explained Variance Score (EVS), and R-squared (R2).
   - Comparing and selecting the best-performing model (Random Forest) based on RMSE.

 ### Conclusion
 
  **Comparing both RMSE the less is Random Forest, therefore it's the best model to use for this project**
  - Random forest adds additional randomness to the model while growing trees. When splitting a node, it searches for the best feature among a random subset of features instead of looking for the most important feature. Thus, it reduces the overfitting problem in decision trees and lessens the variance, improving accuracy. The random forest technique can also handle big data with numerous variables running into thousands. It can automatically balance data sets when a class is more infrequent than other classes in the data.

  **Why is random forest better than linear regression?**
    Linear Models have very few parameters, while Random Forests have a lot more. That means that Random Forests will overfit more easily than a Linear Regression.
    
