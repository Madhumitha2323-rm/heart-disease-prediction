# ❤️ Heart Disease Prediction

## 📌 About the Project

This project uses machine learning techniques to predict the presence of heart disease based on medical attributes.

The project includes data preprocessing, model training, prediction, evaluation, confusion matrix visualization, feature importance analysis, and comparison of different machine learning algorithms.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🤖 Machine Learning Algorithms

The following classification algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

## 📂 Project Files

### 1. `HeartDisease.ipynb`

This notebook includes:

- Loading and exploring the dataset
- Separating features and target
- Train-test split
- Logistic Regression
- Model prediction
- Accuracy, Precision, Recall and F1-score
- Confusion Matrix
- KNN classification
- Testing different K values

### 2. `day8.ipynb`

This notebook includes:

- Data preprocessing
- Decision Tree Classifier
- Decision Tree visualization
- Testing different tree depths
- Random Forest Classifier
- Feature importance analysis
- Testing different numbers of estimators and tree depths
- Comparison of multiple machine learning models

## 📊 Model Comparison

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

Based on the experiments in the notebooks, the Decision Tree model achieved an accuracy of approximately **66.67%** on the test data in the shown experiment.

## 📈 Dataset

The project uses a heart disease dataset containing medical attributes such as:

- Age
- Sex
- Chest Pain Type (CP)
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- and other features

The target variable indicates the presence or absence of heart disease.

## 🎯 Objective

The main objective of this project is to apply different machine learning classification algorithms and compare their performance for heart disease prediction.

## 🚀 How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
