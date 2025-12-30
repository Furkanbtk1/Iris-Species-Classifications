# Iris Species Classification

This project implements a comparative analysis of various Machine Learning models to predict flower species (Setosa, Versicolor, Virginica) using the famous **Iris Dataset**.

## 📋 Project Overview
The project covers the complete data science pipeline, from data loading to model evaluation:
* **Exploratory Data Analysis (EDA):** Structural examination of the dataset.
* **Data Visualization:** Analysis of feature relationships using Seaborn and Matplotlib.
* **Data Preprocessing:** Categorical encoding with `LabelEncoder` and splitting data into training/testing sets.
* **Model Training & Optimization:** Fine-tuning models using `GridSearchCV` for optimal performance.

## 📊 Visualization Techniques Used
* **Pairplot:** Visualizing all pairwise relationships between features.
* **Correlation Heatmap:** Analyzing correlation coefficients between variables.
* **KDE Plots:** Distribution and density analysis of features by species.
* **Scatter Plots:** Clustering analysis of Sepal and Petal measurements.

## 🤖 Model Performance and Accuracy
Based on the notebook results, the accuracy scores on the test set are as follows:

| Model | Accuracy Score | Key Highlights |
| :--- | :--- | :--- |
| **Logistic Regression** | **100%** | Optimized with `C=100`, `penalty='l2'`, and `solver='newton-cg'`. |
| **Support Vector (SVC)** | **97.3%** | Fine-tuned using RBF kernel with `C=1` and `gamma=0.1`. |
| **Naive Bayes** | **100%** | Achieved perfect classification using the GaussianNB algorithm. |

