# 🎬 Movie Rating Prediction

### CodSoft Data Science Internship — Task 2

## 📌 Project Overview

This project predicts the rating of an Indian movie using machine learning techniques.

The dataset contains information about Indian movies, including features such as year, duration, genre, number of votes, director, and actors.

The project demonstrates a complete machine learning workflow, including data cleaning, preprocessing, exploratory analysis, feature engineering, model training, evaluation, comparison, and model saving.

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict movie ratings based on available movie-related features.

Two regression algorithms were implemented and compared:

- Linear Regression
- Random Forest Regressor

---

## 📊 Dataset

The project uses the **IMDb Movies India** dataset.

### Dataset Features

The original dataset contains the following columns:

- `Name` — Movie name
- `Year` — Release year
- `Duration` — Movie duration
- `Genre` — Movie genre
- `Rating` — Movie rating
- `Votes` — Number of votes
- `Director` — Movie director
- `Actor 1` — Lead actor
- `Actor 2` — Second actor
- `Actor 3` — Third actor

### Dataset Size

- Original dataset: **15,509 records**
- Records after cleaning: **7,919 records**
- Total features: **10**

---

## 🧹 Data Preprocessing

The dataset was cleaned and prepared before training the machine learning models.

The preprocessing steps included:

1. Handling missing values
2. Removing unnecessary or invalid records
3. Cleaning numerical columns
4. Converting movie year and duration into numerical values
5. Processing categorical features
6. Encoding categorical variables
7. Separating features and target variable
8. Splitting the dataset into training and testing sets

The target variable for prediction is:

`Rating`

---

## 🤖 Machine Learning Models

### 1. Linear Regression

Linear Regression was used as a baseline regression model for predicting movie ratings.

Evaluation results:

- MAE: **1.0150**
- RMSE: **1.2762**
- R² Score: **0.1240**

### 2. Random Forest Regressor

Random Forest Regressor was also trained to capture more complex relationships between the movie features and ratings.

Evaluation results:

- MAE: **0.8587**
- RMSE: **1.1415**
- R² Score: **0.2991**

### 🏆 Best Model

Based on the evaluation results, the **Random Forest Regressor** performed better than Linear Regression in this experiment.

It achieved:

**R² Score: 0.2991**

and

**RMSE: 1.1415**

---

## 🔮 Example Prediction

The trained model can be used to predict the rating of a movie based on its features.

Example predicted rating:

**6.39**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```text
Task2_Movie_Rating/
│
├── dataset/
│   └── IMDb Movies India.csv
│
├── model/
│   └── movie_rating_model.pkl
│
├── Movie_Rating_Prediction.ipynb
├── README.md
└── requirements.txt