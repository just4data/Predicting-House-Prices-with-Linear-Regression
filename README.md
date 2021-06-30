# Predicting-House-Prices-with-Linear-Regression
Real Estate Price Prediction with Regression


This dataset comes from a Kaggle competition named "[House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)". The dataset is the prices and features of residential houses sold from 2006 to 2010 in Ames, Iowa, obtained from the Ames Assessor's Office. The competition goal is to predict sale prices for homes through a given training and testing data set in csv format as well as a data dictionary.

Although the dataset is relatively small with only 1460 examples, it contains 79 features describing almost every aspect of the house such as areas of the houses, types of the floors, and numbers of bathrooms. Such large amounts of features enable us to explore various techniques to predict the house prices.


**Training:** The training data consists of 1,460 examples of houses with 79 features describing every aspect of the house. We are given sale prices (labels) for each house. The training data is what we will use to "learn" our models.

**Testing:** The test data set consists of 1,459 examples with the same number of features as the training data. The test data set excludes the sale price because this is what we are trying to predict.


## Project Pipeline

Generally speaking, machine learning projects follow the same process. Data exploration, data cleaning, exploratory data analysis, feature engineering and finally machine learning. The pipeline is not linear and you might find you have to jump back and forth between different stages.

1. Exploratory Data Analysis
2. Data Preprocessing
    1. Fixing Skewness and Outliers
    1. Encoding Categorical Data
    1. Imputing Missing Values
3. Modelling
4. Submission




