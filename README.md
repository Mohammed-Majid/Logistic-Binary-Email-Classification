# Email Binary Classification using Logistic Regression
This repository contains code for a binary classification task: predicting whether an email is spam (1) or ham (0) using logistic regression.

## Overview
The main script email_classification.py demonstrates the process of:

- Pre-processing: Loading the dataset, checking for missing values, and splitting it into training and testing sets.
- Feature Extraction: Utilizing TF-IDF Vectorization to convert text data into numerical features.
- Modeling: Training a logistic regression model on the extracted features.
- Evaluation: Assessing the model's performance on both training and testing data, including accuracy, confusion matrix, and classification report.
- Prediction: Accepting user input (email text) and predicting whether it's spam or ham.

## Usage
- Clone the Repository

- Install Dependencies: Make sure you have the necessary dependencies installed. You can install them using pip:
```
pip install numpy pandas scikit-learn seaborn
```
- Run the Script

- Input Email: When prompted, enter an email text to classify it as spam or ham.

## Dataset
The dataset email_classification.csv contains email texts labeled as spam or ham.

## Requirements
- Python 3.x
- numpy
- pandas
- scikit-learn
- seaborn
