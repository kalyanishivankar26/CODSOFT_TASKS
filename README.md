# Titanic Survival Prediction 🚢

## CodSoft Data Science Internship — Task 1

### 📌 Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning.

The project follows a complete Machine Learning workflow, including:

- Data loading
- Data exploration
- Missing value handling
- Data preprocessing
- Feature engineering
- Model training
- Model evaluation
- Model comparison
- Model saving

Two classification algorithms were implemented and compared:

1. Logistic Regression
2. Random Forest Classifier

---

## 📊 Dataset

The project uses the Titanic passenger dataset.

The dataset contains information such as:

- Passenger class
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket fare
- Port of embarkation
- Survival status

The target variable is:

`Survived`

Where:

- `0` = Did not survive
- `1` = Survived

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

## 🔄 Machine Learning Workflow

### 1. Data Loading

The Titanic dataset was loaded using Pandas.

### 2. Data Preprocessing

Missing values were identified and handled.

- Age → Median imputation
- Embarked → Mode imputation
- Cabin → Filled with `Unknown`

Unnecessary columns were removed.

### 3. Feature Encoding

Categorical features such as `Sex` and `Embarked` were converted into numerical features using one-hot encoding.

### 4. Train-Test Split

The dataset was divided into training and testing sets using an 80:20 split.

### 5. Model Training

Two classification models were trained:

- Logistic Regression
- Random Forest Classifier

### 6. Model Evaluation

The models were evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix

### 7. Model Comparison

The models were compared based on their test accuracy.

Random Forest achieved approximately **82.12% accuracy** in this experiment.

---

## 📈 Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | ~82% |
| Random Forest | 82.12% |

The difference between the two models is small, but Random Forest achieved the higher accuracy on this particular train-test split.

---

## 📁 Project Structure

```text
Task1_Titanic/
│
├── dataset/
│   └── train.csv
│
├── images/
│
├── model/
│   ├── titanic_model.pkl
│   └── random_forest_titanic.pkl
│
├── notebook/
│
├── README.md
├── requirements.txt
└── Titanic_Survival_Prediction.ipynb
---

## 🚀 How to Run

### 1. Install the required libraries

```bash
pip install -r requirements.txt