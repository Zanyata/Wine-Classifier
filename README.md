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
