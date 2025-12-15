# Cervical Cancer Prediction with Machine Learning

## Overview
This project aims to predict the risk of cervical cancer using machine learning techniques. An XGBoost classifier is trained on clinical and demographic data to classify patients based on their likelihood of developing cervical cancer.

## Dataset
- Source: Hospital Universitario de Caracas, Venezuela
- Total Records: 858 patients
- Features:
  - Demographic information
  - Number of pregnancies
  - Smoking habits
  - Sexually Transmitted Diseases (STD)
  - Historical medical records

## Project Workflow
1. Exploratory Data Analysis (EDA) and visualization
2. Data cleaning and preprocessing
3. Splitting data into training and testing sets
4. Training the XGBoost classifier
5. Evaluating model performance

## Model Performance
| Dataset       | Accuracy |
|--------------|----------|
| Training Set | 99.562%  |
| Test Set     | 95.348%  |

## Technologies Used
- Python
- XGBoost
- Scikit-learn
- NumPy
- Pandas
- Seaborn
- Plotly
- Jupyter Notebook

## Installation
Open Anaconda Prompt or terminal and install the required dependencies:

```bash
pip install --upgrade pip
pip install numpy
pip install pandas
pip install seaborn
pip install plotly
pip install jupyterthemes
pip install xgboost

