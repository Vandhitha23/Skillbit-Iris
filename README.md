# 🌸 Iris Flower Classification using Machine Learning

## 📌 Project Overview
This project implements a machine learning model to classify iris flowers into different species based on their physical measurements.
The model predicts whether a flower belongs to one of the following classes:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

The classification is performed using the Logistic Regression algorithm.

## 📊 Dataset
The dataset used in this project is IRIS.csv, which contains 150 iris flower samples.
Each sample has the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (target label)

## ⚙️ Technologies Used
- Python
- Pandas
- Scikit-learn

## 🧠 Machine Learning Workflow
1. Load the dataset from a CSV file
2. Separate input features and target labels
3. Split the dataset into training and testing sets
4. Train a Logistic Regression classifier
5. Evaluate the model using accuracy and classification metrics
6. Predict the species of a new iris flower

## 📈 Model Performance
The trained model achieved the following results on the test dataset:

- Accuracy: 100%
- Precision: 1.00
- Recall: 1.00
- F1-score: 1.00

This indicates that the model correctly classified all test samples.

## 🔮 Example Prediction
Input values:
- Sepal Length: 5.1
- Sepal Width: 3.5
- Petal Length: 1.4
- Petal Width: 0.2

Output:
- Predicted Species: Iris-setosa

## 📂 Project Structure
├── IRIS.csv
├── iris_classification.py
└── README.md

## 🚀 How to Run the Project
1. Install the required libraries:
pip install pandas scikit-learn

2. Run the Python script:
python iris_classification.py

## ✅ Conclusion
This project demonstrates a simple and effective machine learning pipeline for multi-class classification using the Iris dataset.
It is ideal for beginners to understand data preprocessing, model training, evaluation, and prediction.

## 👤 Author
Sheldon
Entry-Level AI & Machine Learning Enthusiast
