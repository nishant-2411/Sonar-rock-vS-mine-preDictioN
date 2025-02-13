# Sonar Rock vs Mine Prediction using Logistic Regression

## Overview
This project implements a *Logistic Regression* model to classify sonar signals as either *rocks or mines* based on given frequency response data.

## Dataset
The dataset consists of sonar signals reflected off *rocks* and *metal mines. Each sample contains **60 numerical attributes* representing energy levels at various frequencies.

## Model & Approach
- *Preprocessing*: Handled missing values, scaled features, and split data into training and test sets.
- *Algorithm*: Logistic Regression for binary classification.
- *Evaluation*: Accuracy, Precision, Recall, and Confusion Matrix.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn 
