# BCA 3rd Year - Data Preprocessing and Cleaning

## Project Overview

This project demonstrates data preprocessing and cleaning techniques
using a sample Stroke dataset.

The dataset is processed using Python, Pandas, NumPy, Matplotlib,
Seaborn, and Scikit-learn.

## Dataset

The original dataset contains information related to stroke prediction,
including demographic, health, and lifestyle attributes.

## Data Preprocessing Steps

The following preprocessing steps were performed:

1. Loading the Excel dataset
2. Initial data exploration
3. Checking missing values
4. Handling missing values
5. Checking and removing duplicate records
6. Removing the ID column
7. Exploratory Data Analysis (EDA)
8. Data visualization
9. Encoding categorical variables
10. Standardizing numerical variables
11. Correlation analysis
12. Feature selection using ANOVA F-test
13. Feature importance using Random Forest
14. Train-test splitting
15. Saving the processed dataset

## Missing Value Handling

Missing BMI values were handled using median imputation.

Missing smoking-status values were replaced with "Unknown".

## Data Scaling

Numerical features were standardized using StandardScaler.

## Feature Selection

Feature ranking was performed using:

- ANOVA F-test
- Random Forest feature importance

## Train-Test Split

The processed data was divided into:

- 80% training data
- 20% testing data

## Output

The final processed dataset is:

`stroke_processed.csv`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook
- GitHub