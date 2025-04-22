# 🏥 Linear Regression Health Costs Calculator

This project is part of the **FreeCodeCamp Machine Learning Certification Challenge**. The objective is to build a machine learning model that predicts healthcare costs using various personal and demographic features.

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

Source: [FreeCodeCamp Project Dataset](https://cdn.freecodecamp.org/project-data/health-costs/insurance.csv)

## 🛠️ How the Model Works

- **Preprocessing**: The categorical features (sex, smoker, region) are one-hot encoded to convert them into numerical format.
- **Model Architecture**: The model uses a simple neural network architecture built with **TensorFlow/Keras**.
- **Evaluation**: The dataset is split into training and testing sets (80%/20%). The model is trained on the training set and evaluated on the test set.
- **Goal**: To achieve a **Mean Absolute Error (MAE)** below $3500 on the test set.

## 🔥 Badge

[![Passing Badge](https://img.shields.io/badge/Passed%20Challenge-✅%20%243500%20-%2336c541)](https://github.com/your-username/health-costs-regression)

## 📈 Results

- **Testing Set MAE**: 2532.58 expenses (successfully passed with error under $3500!)
- **Model Evaluation**: The model performs well, with the Mean Absolute Error (MAE) of the model predictions well under the required threshold.

## 🖼️ Model Predictions

![Model Predictions](https://github.com/NyxBelle/health-costs-regression/raw/main/predictions.png)

## 📥 How to Run

1. Open the notebook in [Google Colab]([https://colab.research.google.com](https://colab.research.google.com/drive/1VkdWVsF-knTtrBV-bHw3XdoR1qM1FMVt?usp=sharing))
2. Install necessary libraries by running the initial cells
3. Run the cells from top to bottom to train and evaluate the model

## 📂 Project Files

- `Linear_Regression_Health_Costs.ipynb`: Main notebook containing the code for training and evaluation of the model.
- `predictions.png`: (Optional) A sample image of the model’s predictions vs. actual values.

## 👨‍💻 Tech Stack

- **TensorFlow** for model building and training
- **Pandas** and **NumPy** for data handling
- **Matplotlib** for data visualization
