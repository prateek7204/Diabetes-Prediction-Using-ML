# Diabetes Prediction Using Machine Learning

This project involves building a machine learning model to predict the likelihood of diabetes in individuals. The dataset used for this project was imported from Kaggle. The project encompasses data cleaning, exploratory data analysis (EDA), model training with various algorithms, and creating a graphical user interface (GUI) for prediction using Tkinter.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Cleaning and EDA](#data-cleaning-and-eda)
- [Model Training](#model-training)
- [Best Model Selection](#best-model-selection)
- [GUI Application](#gui-application)

## Introduction
Diabetes prediction is a crucial task to ensure early diagnosis and treatment. In this project, we explore various machine learning algorithms to build an effective diabetes prediction model. The project culminates in a user-friendly GUI application where users can input medical information and get a prediction result.

## Dataset
The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/). It contains labeled medical data, with labels indicating whether an individual has diabetes or not.

## Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tkinter

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib tkinter
```

## Data Cleaning and EDA
Data cleaning involves removing any irrelevant or missing data, and processing the data to make it suitable for analysis. Exploratory Data Analysis (EDA) helps in understanding the distribution of data and identifying key patterns and trends.

Key steps include:

- Removing duplicates and null values
- Handling missing data
- Visualization of feature distributions and other relevant statistics

## Model Training
We experimented with several machine learning models to find the best one for this prediction task:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Each model was trained and evaluated based on its accuracy.

## Best Model Selection
After evaluating all models, we found that the Random Forest provided the highest accuracy. Therefore, we selected Random Forest as our final model for the diabetes prediction task.

## GUI Application
To make the prediction tool user-friendly, we created a GUI using Tkinter. The GUI allows users to input medical information and receive a prediction result indicating whether the individual is likely to have diabetes or not.

## Screenshot of the GUI
![diabetes prediction tkinter](https://github.com/yourusername/Diabetes-Prediction/assets/sample-image.png)

---
