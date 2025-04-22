# 🏥 Linear Regression Health Costs Calculator

This project is part of the [freeCodeCamp Machine Learning with Python](https://www.freecodecamp.org/learn/machine-learning-with-python/) course. The objective is to build a machine learning model that predicts healthcare costs using various personal and demographic features.

## 🚀 Project Overview

The model uses **linear regression** to predict healthcare costs based on a set of features. The dataset includes information such as age, BMI, smoking habits, and geographical region. The goal is to minimize the Mean Absolute Error (MAE) to under $3500.

## 📊 Dataset

The dataset contains the following columns:

- `age`: Age of the individual
- `sex`: Gender of the individual (Male/Female)
- `bmi`: Body Mass Index (BMI) of the individual
- `children`: Number of children/dependents covered by the insurance
- `smoker`: Whether the individual smokes (Yes/No)
- `region`: Geographical region of the individual
- `expenses`: Healthcare costs (target value)

## 🛠️ What This Model Does
- Preprocesses categorical features using one-hot encoding
- Splits the dataset into training and testing sets (80/20)
- Normalizes the data
- Builds a neural network using TensorFlow/Keras
- Trains and evaluates the model
- Achieves a Mean Absolute Error (MAE) of under $3500 on test data
- 
## 🔥 Badge

[![Passing Badge](https://img.shields.io/badge/Passed%20Challenge-✅%20%243500%20-%2336c541)](https://github.com/your-username/health-costs-regression)

## 📈 Results

- **Testing Set MAE**: 2532.58 expenses (successfully passed with error under $3500!)
- **Model Evaluation**: The model performs well, with the Mean Absolute Error (MAE) of the model predictions well under the required threshold.

Run it in Google Colab:  
[📓 Open Notebook](https://colab.research.google.com/drive/1VkdWVsF-knTtrBV-bHw3XdoR1qM1FMVt?usp=sharing)

## 👨‍💻 Tech Stack
- Python 🐍
- TensorFlow / Keras
- Google Colaboratory
- Pandas / NumPy
- Matplotlib
