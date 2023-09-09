# Credit EDA (Exploratory Data Analysis)

## Overview
This project conducts Exploratory Data Analysis (EDA) on a credit dataset. EDA is a crucial step in understanding and analyzing the data before proceeding with more advanced techniques. This project includes data cleaning, visualization, and deriving insights from the dataset.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## Data
- Dataset: "application_data.csv"
- Loading the dataset: `app_data = pd.read_csv("application_data.csv")`
- Checking dataset information: `app_data.info()`

## Data Cleaning
- Handling missing values: Removing columns with over 47% missing data and imputing others.
- Data type adjustments: Converting date-related columns into "YEARS" categories.

## Data Visualization
- Visualizing credit amount distribution.
- Categorizing credit amounts.
- Analyzing age distribution.
- Extracting demographic insights.

## Insights
Key insights from the EDA:
1. The significance of contract types, housing types, and income types in predicting successful payments.
2. The need to target specific demographic groups for improved risk management.
`
## Data Source

The data used in this project was obtained from Kaggle, a platform for data science and machine learning enthusiasts. Kaggle provides a valuable resource for datasets, competitions, and collaborative data science projects.

The specific dataset used in this project can be found at the following Kaggle URL:

[Credit EDA Case Study-Kaggle Dataset](https://www.kaggle.com/datasets/venkatasubramanian/credit-eda-case-study)

We would like to express our gratitude to the contributors and data providers on Kaggle for making this dataset available for analysis and research purposes.


## Conclusion
This EDA provides a comprehensive understanding of the credit dataset, serving as a foundation for further analysis and informed decision-making.
