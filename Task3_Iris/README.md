# 🌸 Iris Flower Classification

A Machine Learning project that classifies Iris flowers into three species:
Setosa, Versicolor, and Virginica.

## 📌 Project Overview

This project uses the Iris dataset to build and compare two
classification models:

- Logistic Regression
- Random Forest Classifier

The models use four flower measurements to predict the Iris species.

## 📊 Dataset

The dataset contains 150 samples and 5 columns.

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target

- Setosa
- Versicolor
- Virginica

The dataset contains 50 samples of each species.

There are no missing values in the dataset.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## 🤖 Machine Learning Models

### 1. Logistic Regression

Accuracy: **96.67%**

### 2. Random Forest Classifier

Accuracy: **90%**

Logistic Regression performed better on the test dataset.

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

A confusion matrix was also generated for the Random Forest model.

## 🔮 Sample Prediction

The model was tested with the following flower measurements:

- Sepal Length: 5.1
- Sepal Width: 3.5
- Petal Length: 1.4
- Petal Width: 0.2

### Prediction

**Setosa**

## 📁 Project Structure

```text
Task3_Iris/
│
├── dataset/
│   └── Iris.csv
│
├── model/
│   ├── logistic_regression_iris.pkl
│   └── random_forest_iris.pkl
│
├── notebook/
│   └── Iris_Classification.ipynb
│
└── README.md