# Titanic Data Cleaning and Preparation

## Description
This repository contains the code and resources for cleaning and preparing the Titanic dataset for machine learning analysis. The Titanic dataset is a well-known dataset used for predictive modeling, where the goal is to predict whether a passenger survived the tragic sinking of the Titanic based on various features such as age, gender, class, and fare.

## Objectives
The main objectives of this project are:
- To explore the dataset and understand its structure and contents.
- To handle missing values effectively to ensure data integrity.
- To convert categorical features into numerical formats suitable for machine learning algorithms.
- To normalize and standardize numerical features to improve model performance.
- To identify and remove outliers that may skew the results of the analysis.

## Key Steps
1. **Data Import and Exploration**: Loaded the Titanic dataset using Pandas and explored its basic information, including data types and missing values.
2. **Handling Missing Values**: Implemented strategies to fill missing values using median for age and mean for fare, and mode for categorical features.
3. **Encoding Categorical Features**: Utilized one-hot encoding to convert categorical variables into numerical format, making them suitable for machine learning models.
4. **Normalization and Standardization**: Applied Min-Max scaling and Standardization techniques to numerical features to ensure they are on a similar scale.
5. **Outlier Detection and Removal**: Visualized outliers using boxplots and removed them based on the Interquartile Range (IQR) method to enhance data quality.

## Files Included
- `task1.ipynb`: Python Notebook containing the data cleaning and preparation code.
- `Titanic-Dataset.csv`: The raw dataset used for analysis.
- `requirements.txt`: A file listing the required Python packages for this project.

## Requirements
To run this project, you need to have Python installed along with the required packages. You can install the necessary packages using the `requirements.txt` file.
