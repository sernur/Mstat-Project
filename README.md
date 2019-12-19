# Mstat-Project

## This is the project for my master degree in statistics. 

In this Jupyter notebook, I analyze a dataset containing information about PhD applicants to major universities. I use machine learning methods to predict if the university admissions committee accepts, waitlists or rejects the application. The main goal of this project is to predict rating score assigned to the student by the committee.

I will use **machine learning** models for **regression and classification**. First, I do prediction on DECISION variable using all other variables including RATING. However, later I will predict RATING using other variables without using DECISION variable

## Contents


Table of Contents
1. Import Libraries
2. Introduction
    - Data Set
    - Variable Description
3. Data Analysis
    - Data Visualization
    - Using groupby
4. Data Prepocessing
    - Handling Missing Values
    - Target variable
    - Converting categorical variables to numeric variables
5. Overview of the Methods.
    - Gradient Descent 
        a. Batch Gradient Descent 
        b. Stochastic Gradient Descent 
        c. Mini-Batch Gradient Descent
    - Neural Networks 
        a. Bulding Blocks: Neurons 
        b. A Simple Example 
        c. Combining Neurons into Neural Network 
        d. Feedforward 
        e. Training a Neural Network

6. Applying Machine Learning to predict DECISION using RATING
    - Decision Tree
    - Logistic Regression
    - Random Forest
    - Stochastic Gradient Descent
    - KNN
    - Gaussian Naive Bayes
    - Perceptron
    - SVM
    - Linear SVM
    - Adaptive Boosting
    - XGBoost
    - Which Model is the best ? Table 1

7. Models with the grid search(to predict Decision), stacking approach and h2oAutoML
    - Decision Tree (DT)
    - Logistic Regression (LG)
    - Random Forest (RF)
    - Stochastic Gradient Descent (SGD)
    - KNN
    - Gaussian Naive Bayes (GNB)
    - Perceptron
    - SVM
    - Linear SVM
    - Adaptive Boosting
    - XGBoost
    - Cat Boost
    - Light GBM
    - Which Model is the best ? Table 4
    - Stacking Approach
    -Using h2o AutoML
8. Estimating the Rating Variable packages
    - Individual Models
    - h2o AutoML
    - h2o GBM
    - h2o RF
    - h2o Deep Learning 
    - Deep Learning Estimator   
9. References
