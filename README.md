# Elevate_task-5
# Titanic Dataset Analysis

This project performs a detailed exploratory data analysis (EDA) on the [Titanic dataset](https://www.kaggle.com/c/titanic), a classic machine learning dataset. It includes data preprocessing, visualization, and insights to understand the factors that influenced passenger survival.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Key Steps](#key-steps)
- [Findings](#findings)

## Project Overview
The goal of this project is to analyze the Titanic passenger data to:
- Identify key features affecting survival
- Handle missing data
- Perform basic visualizations and EDA
- Prepare for potential predictive modeling

## Dataset
The dataset includes data for 891 passengers with the following key features:
- Survived: Survival (0 = No, 1 = Yes)
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Sex, Age, SibSp, Parch, Fare, Cabin, Embarked

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## Key Steps
1. Data Loading and Initial Exploration
2. Handling Missing Values
3. Visualizing Distributions
4. Grouping and Aggregation (e.g., survival by gender/class)
5. Preparing insights for modeling

## Findings
- Most passengers did not survive (549 died vs 342 survived).
- Higher survival rate observed in 1st class and among females.
- Missing data was notable in Age, Cabin, and Embarked columns.
