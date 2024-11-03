# Diabetes Prediction

This repository contains a machine learning project for predicting diabetes based on a dataset. This project is part of a course assignment focused on exploring various data preprocessing and machine learning techniques, specifically logistic regression and k-nearest neighbors (KNN).

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Overview

The aim of this project is to build predictive models for diabetes diagnosis using data preprocessing techniques, logistic regression, and KNN classifiers. By exploring different approaches and comparing model performances, we gain insights into the best practices for predicting medical conditions using machine learning.

## Dataset

The dataset used for this project is provided as part of the course. It includes various features related to patient health, which may contribute to the likelihood of a diabetes diagnosis. 

### Features
The dataset includes columns representing factors such as:
- Pregnancies
- Glucose
- Blood pressure
- Skin thickness
- Insulin
- BMI
- Diabetes pedigree function
- Age
- Outcome

Each row represents data for a unique patient, with the Outcome variable indicating diabetes presence (1) or absence (0).

## Project Structure

- **data/**: Contains the dataset file
- **notebooks/**: Jupyter notebooks for exploratory data analysis and modeling
- **scripts/**: Python scripts for data preprocessing, model training, and evaluation
- **results/**: Model performance results and visualizations
- **README.md**: Project overview and instructions
- **requirements.txt**: List of dependencies


## Requirements

To run this project, you'll need to install the dependencies listed in `requirements.txt`. You can do this by running:

```bash
pip install -r requirements.txt
```

## Main Packages

- numpy
- pandas
- scikit-learn
- matplotlib

## Usage

### 1. Data Preprocessing:
The data preprocessing script or notebook handles missing values, standardizes/normalizes features, and prepares the dataset for model training.
### 2. Model Training:
- **Logistic Regression**: Implements logistic regression for baseline prediction.
- **K-Nearest Neighbors (KNN)**: Trains a KNN model to evaluate performance compared to logistic regression.
### 3. Evaluation:
Each model is evaluated using common metrics like accuracy, precision, recall, and F1-score.

## Example 

To run the models, you can use the scripts provided:

```bash
python scripts/logistic_regression.py
python scripts/knn.py
```

These scripts will output evaluation metrics and may save the trained models for future use.

## Result
The results of each model’s performance are stored in the results/ folder. Initial findings and comparisons between logistic regression and KNN are summarized in a final report.

## Acknowledgements

This project is part of the machine learning course at Hochschule Landshut. Thanks to the instructors and course facilitators for their guidance.
















