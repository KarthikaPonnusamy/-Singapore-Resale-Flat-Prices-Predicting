# -Singapore-Resale-Flat-Prices-Predicting
## Problem Statement:
The objective of this project is to develop a machine learning model and deploy it as a user-friendly web application that predicts the resale prices of flats in Singapore. This predictive model will be based on historical data of resale flat transactions, and it aims to assist both potential buyers and sellers in estimating the resale value of a flat.

## Skills:
  * Data Wrangling:
  * EDA (Exploratory Data Analysis):
  * Model Building:
  * Model Deployment:
## libraries used:
  * Python -- Programming Language
  * pandas -- Python Library for Data Visualization
  * numpy -- Fundamental Python package for scientific computing in Python
  * streamlit -- Python framework to rapidly build and share beautiful machine learning and data science web apps
  * scikit-learn -- Machine Learning library for the Python programming language

## Project Workflow:
 * The Resale Flat Prices dataset has five distinct CSV files, each representing a specific time period. These time periods are 1990 to 1999, 2000 to 2012, 2012 to 2014, 2015 to 2016, and 2017 onwards. Therefore,       it is essential to merge the five distinct CSV files into a unified dataset.
 * The data will be converted into a format that is appropriate for analysis, and any required cleaning and pre-processing procedures will be carried out. Relevant features from the dataset, including town, flat       type, storey range, floor area, flat model, and lease commence date will be extracted. Any additional features that may enhance prediction accuracy will also be created.
 * The objective of this study is to construct a machine learning regression model that utilizes the RandomForestRegressor to accurately forecast the continuous variable 'resale_price'.

 * The objective is to develop a Streamlit webpage that enables users to input values for each column and get the expected resale_price value for the flats in Singapore.

