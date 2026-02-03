# Exam Score Prediction using Machine Learning Models

This project aims to predict student's exames score, using the dataset Exam_Score_Prediction from Kaggle.
Three models are fitted : linear regression, KNN Regressor and Neural Network. 
The performance of these models with respect to MSE are assessed and Neural Network shows better performance.

## Main steps are: 
- data preprocessing
- cross validation
- model stability assessing.

## Project Overview

The goal of this project is to build predictive models that estimate students’ exam scores based on several academic and personal characteristics.

## Dataset Description

### Dataset: Exam_Score_Prediction.csv (Kaggle)

### Target Variable:exam_Score

### Features:
- age 
- gender
- course
- study_hours
- class_attendance
- internet_access
- sleep_hours
- sleep_quality
- study_method
- facility_rating
- exam_difficulty


## Models adjusted
- Linear Regression

- K-Nearest Neighbors Regressor (KNN)

- Neural Network

## Model Evaluation

Evaluation was performed using 10-fold cross-validation with the metric neg_mean_squared_error 



## Conclusion:
- Linear Regression provides better predictive accuracy for this dataset than KNN 
- Neural Network shows better performance than both Linear regression and KNN regressor.

This suggests that the relationship between features and exam score is more complex to be explained by
linear regression or KNN regressor making Neural Network good feed.

## Author Luc AGBOGNISSO, MSc student in Mathmatical Sciences at AIMS Ghana