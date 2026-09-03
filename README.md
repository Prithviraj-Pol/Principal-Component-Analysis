# Principal Component Analysis — Iris Dataset

## 📌 Overview

This project was completed as part of a **4-Day Machine Learning Workshop at MIT Thandavapura**.

It demonstrates **Principal Component Analysis (PCA)** on the Iris dataset for dimensionality reduction and visualization. The project includes data preprocessing, feature standardization, PCA transformation, explained variance analysis, and visualization using the first two principal components.

## 🎯 Objectives

* Load and inspect the Iris dataset
* Check data types and missing values
* Perform descriptive statistical analysis
* Standardize numerical features
* Apply Principal Component Analysis (PCA)
* Analyze explained variance
* Visualize data in a reduced two-dimensional space

## 🔬 Methodology

The project follows these steps:

```text id="4q3t8s"
Iris Dataset
      ↓
Data Inspection
      ↓
Data Standardization
      ↓
Principal Component Analysis (PCA)
      ↓
Explained Variance Analysis
      ↓
Scree Plot
      ↓
2D PCA Visualization
```

The Iris features are standardized using `StandardScaler` before applying PCA.

## 📊 Dataset

The **Iris dataset** contains four numerical features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable represents the Iris flower species.

## 📈 PCA Analysis

A **Scree Plot** is used to visualize the proportion of variance explained by each Principal Component.

The first two Principal Components are then used to create a two-dimensional visualization of the dataset, allowing the transformed feature space to be explored by species.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## 📁 Project Files

```text id="qk2h2c"
Principal_Component_Analysis.ipynb
principal_component_analysis.py
README.md
```

## 🏫 Workshop Information

**Workshop:** 4-Day Machine Learning Workshop
**Institution:** MIT Thandavapura
**Domain:** Machine Learning & Data Science
**Project:** Principal Component Analysis

## 📚 Learning Outcomes

This project provided practical experience in **dimensionality reduction, feature standardization, explained variance analysis, and visualization of high-dimensional data using Principal Component Analysis (PCA).**

---

*Developed as part of the practical learning activities during the 4-Day Machine Learning Workshop at MIT Thandavapura.*
