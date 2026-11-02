# Titanic Dataset – Data Preparation and EDA

## Project Overview
This project focuses on data preparation and Exploratory Data Analysis (EDA) using the Titanic dataset.

## Objectives
- Inspect the dataset and understand its structure.
- Identify and handle missing values.
- Check duplicate records and data consistency.
- Perform exploratory data analysis.
- Visualize important patterns using graphs.
- Encode categorical features.
- Scale numerical features.
- Save the prepared dataset as a CSV file.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
Titanic dataset obtained from the Seaborn open dataset repository.

Source: https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv

## Data Preparation
- Missing numerical values handled using median.
- Missing categorical values handled using mode.
- Deck column removed due to excessive missing values.
- Duplicate records inspected and documented.
- Categorical variables encoded using One-Hot Encoding.
- Age and Fare scaled using StandardScaler.

## Files Included
1. Titanic_Data_Preparation_EDA.ipynb
2. Titanic_Original_Dataset.csv
3. Titanic_Prepared_Dataset.csv

## Conclusion
The project demonstrates the importance of data cleaning, exploratory data analysis, encoding and feature scaling before using data in a machine learning workflow.
