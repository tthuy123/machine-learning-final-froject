
# Machine Learning Final Project

This repository contains the final project for our Machine Learning course at UET-VNU. It demonstrates the application of various machine learning techniques, including feature engineering, clustering, and ensemble modeling.

## Table of Contents

- [Project Description](#project-description)
- [File Descriptions](#file-descriptions)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Project Description

This project explores different machine learning models and techniques to solve https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use competition . The main focus is on:
- Feature engineering
- Clustering using DBSCAN and t-SNE
- Regression models like LightGBM and XGBoost
- Ensemble learning for model optimization

## File Descriptions

- **`LGBM.ipynb`**: Implementation of LightGBM regression model with detailed feature engineering.
- **`xgboost.ipynb`**: Application of XGBoost with pure feature engineering to improve model accuracy.
- **`dbscan-clustering-t-sne.ipynb`**: Clustering analysis using DBSCAN and visualization with t-SNE. Includes preprocessing to handle missing values in the dataset.
- **`ensemble_final.ipynb`**: Combines multiple models for ensemble learning to boost performance.
- **`README.md`**: This documentation file.

## Installation

To run the notebooks in this repository, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/machine-learning-final-project.git
   cd machine-learning-final-project
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

   *(Ensure you have created a `requirements.txt` file listing the dependencies. If not, I can help you with that.)*

4. Launch Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook
   ```

## Usage

1. Open the relevant notebook (e.g., `LGBM.ipynb`, `dbscan-clustering-t-sne.ipynb`).
2. Execute the cells sequentially to reproduce the results.
3. Modify the code as needed to experiment with different hyperparameters or data configurations.

## Acknowledgements

This project is part of my coursework for the Machine Learning class at [Your University Name]. I would like to thank our instructors for their guidance and support throughout the course.
