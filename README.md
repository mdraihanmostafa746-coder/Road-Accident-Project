# Road Accident Severity Prediction and Accident Risk Analysis

## Project Overview
This project focuses on analyzing road accident data and applying Machine Learning techniques to predict accident severity and understand accident patterns.

The main goal is to identify factors associated with road accidents and build models that can help analyze accident severity.

## Dataset
- Source: Kaggle – Road Traffic Accidents
- File: `train.csv`
- Records: 8,210
- Features: 33

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Model Comparison and Conclusion

## Machine Learning Models
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest

## Project Structure
```text
Road-Accident-ML/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── 01_Dataset_Inspection.ipynb
│
├── reports/
│
└── README.md
```

## Key Objectives
- Analyze accident severity patterns.
- Understand the relationship between accident conditions and severity.
- Predict accident severity using Machine Learning.
- Compare different models using evaluation metrics.

## Limitations
The dataset contains an imbalanced target variable, with fatal accidents representing a small proportion of records. Therefore, model performance should be evaluated using precision, recall and F1-score, not accuracy alone.

## Author
**Md Raihan Mostafa**