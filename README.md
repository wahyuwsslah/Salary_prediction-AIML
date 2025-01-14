# Salary Prediction Analysis Using Machine Learning

## Introduction
This project aims to predict employee salary based on years of work experience using various machine learning models.

## Data Preparation
- The data is taken from the file 'salary_data.csv'.
- The dataset contains the information: Employee ID, years of experience, and salary
- Total 100 employee data with 3 columns

## Exploratory Data Analysis (EDA)
- Visualization using scatter plot to see the relationship between experience and salary
- Examination of data descriptive statistics
- Checking for duplicate data and missing values

## Data preprocessing
- Removal of duplicate data
- Checking for missing values (not found)
- Data division into training (75%) and testing (25%)

## Model Implementation

### A. Linear Regression
- Model: y = 1641.366 + 103.197x
- Performance metrics:
  - MSE Train and Test
  - R² Score for model evaluation

### B. Decision Tree
- Implementation using DecisionTreeRegressor
- Visualization of prediction results
- Performance evaluation with MSE and R²
- Model is saved in PKL format

### C. Random Forest
- Implementation using RandomForestRegressor
- Visualization of prediction results
- Performance evaluation using the same metrics
- Model is saved in PKL format

## Technical Features
- Using libraries: pandas, matplotlib, seaborn, scikit-learn
- Implementation of three different machine learning models
- Model storage using joblib
- Visualization of results using matplotlib
## Conclusion
This project demonstrated the use of three different machine learning models for salary prediction, each with its own advantages and characteristics. Each model was evaluated using standard metrics and can be used according to specific needs.
