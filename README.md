# Exam Score Prediction using Machine Learning Models

This project aims to predict student's exames score, using the dataset Exam_Score_Prediction from Kaggle.
Three models are fitted : linear regression, KNN Regressor and Neural Network. 
The performance of these models with respect to MSE are assessed and both Linear regression and Neural Network show better performance.

## Main steps are 
- data preprocessing
- cross validation
- model stability assessing.

## Project Overview

The goal of this project is to build predictive models that estimate students’ exam scores based on several academic and personal characteristics.

## Dataset Description

### Dataset: Exam_Score_Prediction.csv (Kaggle)

### Target Variable:exam_Score

### Features
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



## Conclusion
- Linear Regression provides better predictive accuracy for this dataset than KNN 
-The Neural Network achieves the best overall performance compared to Linear Regression and KNN; however, it exhibits sensitivity to random
initialization, with one out of sixteen runs (6.25%) resulting in a significantly higher MSE, indicating occasional model instability.

## This suggests that 
- The relationship between the features and exam scores appears to be complex and nonlinear.
- The observed instability may be due to the limited dataset size or suboptimal hyperparameter tuning, suggesting that further optimization 
could improve model stability.
