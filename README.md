# Walmart Black Friday Sales Analysis

This repository contains a data science project focused on analyzing and predicting sales data during Walmart's 2023 Black Friday sale. The project leverages data preprocessing, exploratory data analysis (EDA), and predictive modeling techniques to uncover insights and build accurate models.

Research Question: How can we predict a user's expenditure in a specific product category based on their profile data?

## Project Overview
Black Friday is one of the biggest shopping events of the year, and understanding customer behavior can provide valuable insights for inventory planning, marketing strategies, and profit optimization.

In this project we: 

* Conducted Exploratory Data Analysis (EDA) to uncover trends and patterns
* Applied one-hot encoding to handle categorical variables
* Split the dataset into training (60%), validation (30%), and testing (10%) sets to prevent overfitting
* Built and evaluated predictive models to forecast purchase behavior

## Recognition
This project earned 2nd place overall at Data@UCI's Winter Project Showcase.

## Methodology
**1. Data Preprocessing**
* Handled missing values and cleaned the dataset
* Applied one-hot encoding to categorical features

**2. Data Splitting**
* Training Set (60%)
* Validation Set (30%)
* Testing Set (10%)

**3. Modeling** 
* Tried different regression models (Linear Regressions, Random Forests, Neural Networks)
* Evaluated models using RMSE and $R^2$ on validation and test sets

## Results
The Random Forest Regressor provides the most accuracy in predicting purchase amount spent for a given user.


[Walmart Project Pitch](https://docs.google.com/presentation/d/1ftQAPWpcRPjzrXyLprgXe9GGze8RU-8292pOfqCCxDE/edit?usp=sharing)
