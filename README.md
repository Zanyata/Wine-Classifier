# Wine Classification Project

This repository contains a machine learning project that classifies wine varieties using the Wine dataset. The project demonstrates data preprocessing, exploratory data analysis (EDA), feature selection, and training of machine learning models, including Logistic Regression and Random Forest classifiers.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Models](#models)
- [Installation](#installation)

## Overview
This project aims to classify wine samples into distinct classes based on their chemical properties. It leverages machine learning techniques to explore both linear and non-linear relationships in the data.

Key highlights include:
- Comprehensive exploratory data analysis (EDA)
- Hyperparameter tuning using GridSearchCV
- Dimensionality reduction using feature importance from Random Forest

## Dataset
The dataset is sourced from the UCI Machine Learning Repository and is accessible via the following [link](https://archive.ics.uci.edu/dataset/109/wine).

### Features
The dataset includes the following attributes:
- Alcohol
- Malic acid
- Ash
- Alkalinity of ash
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

### Target
The target variable is the wine class, represented as:
- Class 1
- Class 2
- Class 3

## Project Structure
```
|-- README.md          # Project description and usage
|-- Wine_classification_2.ipybn  # Main script with all code
|-- data/              # Folder containing the dataset 
```

## Features
1. **Data Preprocessing**:
   - Data scaling
   - Visualizations: Correlation heatmap, boxplots
2. **Exploratory Data Analysis (EDA)**:
   - Class distribution
   - Outlier detection
3. **Machine Learning Models**:
   - Logistic Regression
   - Random Forest Classifier
4. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1 Score
   - Confusion matrix visualization
   - Feature importance analysis

## Models
### Logistic Regression
- A baseline model chosen for its interpretability and ability to handle linearly separable data efficiently.
- Hyperparameter tuning via GridSearchCV.

### Random Forest Classifier
- A robust ensemble model used to handle non-linear data.
- Provides feature importance metrics for dimensionality reduction.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Wine-Classifier.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Wine-Classifier
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
---

For further improvements or questions, feel free to create an issue or contact the repository owner.

