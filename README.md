# Red Wine Quality Testing

## Overview
This project aims to analyze and predict the quality of red wine based on various physicochemical properties. The dataset used in this project contains information about different attributes of red wine, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality.

## Dataset
The dataset used in this project is available as a CSV file (`WineQT.csv`). It consists of 1143 rows and 12 columns. Some of the attributes include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (target variable)

## Tools and Libraries
- Python programming language
- Jupyter Notebook
- Libraries:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Plotly Express
  - Scikit-learn
  - XGBoost

## Exploratory Data Analysis (EDA)
The EDA phase includes:
- Data visualization using various plots like count plot, heatmap, scatter plot, violin plot, and box plot to understand the distribution and relationships between different attributes.
- Descriptive statistics to gain insights into the central tendency, dispersion, and shape of the dataset.

## Data Preprocessing
- Data normalization: Scaling the numerical features to a standard range.
- Train-test split: Splitting the dataset into 80% training data and 20% testing data for model evaluation.

## Models and Evaluation
The following machine learning models are trained and evaluated for predicting wine quality:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Classifier (SVC)

Model performance metrics such as accuracy score, F1-score, and classification report are utilized to evaluate the models. The model with the highest performance metrics is considered for further analysis.

## Model Comparison
A comparative analysis of the models based on their accuracy and F1-score is presented, helping to identify the best-performing model for predicting wine quality.

## Conclusion
This project provides insights into the quality of red wine based on its physicochemical properties and demonstrates the effectiveness of machine learning models in predicting wine quality. It serves as a valuable resource for wine manufacturers and enthusiasts to understand the factors influencing wine quality and optimize production processes.
