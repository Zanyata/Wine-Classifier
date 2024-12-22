# Wine-Classifier
The goal of this classification project is to assess wine type (from 3 different cultivars) by analyzing 13 chemical constituents. This classification task is well-suited for testing and benchmarking various machine learning algorithms due to its "well-behaved" class structures.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Installation
To get started, clone this repository to your local machine:
   ```
   git clone https://github.com/Zanyata/Wine-Classifier.git
   ```
## Usage
1. Running the project
   * The project is organized into the following folders:
      * data/: Contains the dataset (CSV file).
      * notebooks/: Contains Jupyter notebooks for analysis and modeling.
To start using the project, open and run the Jupyter Notebook in the notebooks/ folder (e.g., notebooks/analysis.ipynb).
2. Colab Version (optional)
If you prefer to use Google Colab for running the project, you can simply upload the notebooks and data to Colab. You can also link to the raw dataset hosted on GitHub (or upload it to Colab directly).
3. Running the code (Example):
After setting up your environment, run the following Python script or Jupyter notebook cells to execute the wine classification analysis:
```
python notebooks/analysis.ipynb
```

## Dependencies
This project requires Python 3.x. To install the necessary dependencies, you can create a virtual environment and use the following command:
```
pip install -r requirements.txt
```
The requirements.txt file includes the necessary libraries:
* Python 3.x
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn
* yellowbrick

## License
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
[link](https://archive.ics.uci.edu/dataset/109/wine)



OR

# Wine Classification Project

This repository contains a machine learning project that classifies wine varieties using the Wine dataset. The project demonstrates data preprocessing, exploratory data analysis (EDA), feature selection, and training of machine learning models, including Logistic Regression and Random Forest classifiers.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview
This project aims to classify wine samples into distinct classes based on their chemical properties. It leverages machine learning techniques to explore both linear and non-linear relationships in the data.

Key highlights include:
- Comprehensive exploratory data analysis (EDA)
- Hyperparameter tuning using GridSearchCV
- Dimensionality reduction using feature importance from Random Forest

## Dataset
The dataset is sourced from the UCI Machine Learning Repository and is accessible via the following [GitHub link](https://raw.githubusercontent.com/Zanyata/Wine-Classifier/refs/heads/main/data/wine.csv).

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
|-- wine_classification.py  # Main script with all code
|-- data/              # Folder containing the dataset (not included in repo)
```

## Features
1. **Data Preprocessing**:
   - Data cleaning and scaling
   - Visualizations: Correlation heatmap, boxplots, and pairplots
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

## Usage
Run the main script to execute the project:
```bash
python wine_classification.py
```

## Results
### Logistic Regression
- Accuracy: ~97% (depending on the dataset split)
- Best hyperparameters found using GridSearchCV.

### Random Forest
- Accuracy: ~98%
- Feature importance identified top contributors to classification.

Confusion matrices and classification reports are displayed for both models to evaluate performance.

---

For further improvements or questions, feel free to create an issue or contact the repository owner.

