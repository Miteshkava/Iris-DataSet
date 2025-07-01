# 🌸 Iris Dataset Analysis and Classification

This project performs exploratory data analysis (EDA) and classification modeling on the famous **Iris flower dataset**. The goal is to classify iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on four features: sepal length, sepal width, petal length, and petal width.

---

## 📁 Project Structure

iris-classification/
├── data/
│ └── iris.csv
├── iris_classification.py
├── requirements.txt
└── README.md

yaml
Copy
Edit

---

## 📌 Dataset Description

The Iris dataset contains 150 records with the following features:

- `sepal_length`: Length of the sepal in cm
- `sepal_width`: Width of the sepal in cm
- `petal_length`: Length of the petal in cm
- `petal_width`: Width of the petal in cm
- `species`: Class label – Setosa, Versicolor, or Virginica

---

## 🎯 Project Objectives

- Load and explore the Iris dataset
- Perform data visualization for feature distributions
- Understand class balance and correlation
- Train multiple classification models
- Compare model performance using accuracy and confusion matrix
- Identify the best-performing model

---

## 🛠️ Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iris-classification.git
   cd iris-classification
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the classification script:

bash
Copy
Edit
python iris_classification.py
Or open it in Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
📊 Features and Output
Scatter plots and pair plots for visual inspection

Heatmap of feature correlation

Models used:

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Support Vector Machine (SVM)

Evaluation:

Accuracy Score

Confusion Matrix

Classification Report

🌟 Sample Insight
Petal length and petal width are the most distinguishing features for identifying species. Setosa is easily separable, while Versicolor and Virginica overlap more.
