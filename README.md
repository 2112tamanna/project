# Student Maths Score Prediction

## Introduction

1. **Problem Statement**: 
   This project aims to understand how various factors such as Gender, Ethnicity, Parental level of education, Lunch, and Test preparation course influence students' performance in tests, specifically math scores.

2. **Data Collection**:
   The dataset used for this project is sourced from Kaggle and consists of 8 columns and 1000 rows.

## Dataset Information

- **gender**: Sex of students (Male/Female)
- **race/ethnicity**: Ethnicity of students (Group A, B, C, D, E)
- **parental level of education**: Parents' final education (e.g., bachelor's degree, some college, master's degree)
- **lunch**: Whether the student had lunch before the test (Standard or Free/Reduced)
- **test preparation course**: Completion status of test preparation course before the test
- **math score**
- **reading score**
- **writing score**

## Project Overview

This project utilizes various machine learning algorithms to predict students' math scores:

1. **Linear Regression**
2. **K-Neighbors Regressor**
3. **Decision Tree**
4. **Random Forest Regressor**
5. **XGBRegressor**
6. **CatBoost Regressor**
7. **AdaBoost Regressor**

## Libraries Used

- **numpy**: For numerical computations
- **pandas**: For data manipulation and analysis
- **scikit-learn**: For machine learning algorithms implementation
- **xgboost**: For gradient boosting
- **catboost**: For gradient boosting on decision trees
- **matplotlib**: For data visualization
- **seaborn**: For statistical data visualization

By following the methodology outlined and using the mentioned libraries, one can reproduce and expand upon the findings of this project.

## Conclusion

The model achieved an accuracy of 88% on the test dataset, with the Linear Regression model being used for prediction.
