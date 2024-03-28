# Student Performance Predictor

## Overview
The Student Performance Predictor is a machine learning project aimed at predicting student performance based on various features such as demographics, study habits, and socioeconomic factors. It utilizes a range of machine learning algorithms and integrates with tools for experiment tracking, pipeline management, and deployment.

## Features
- **Data Cleaning and Preprocessing**: The project includes thorough data cleaning and preprocessing steps to handle missing values, outliers, and ensure data quality.
- **Data Visualization**: Matplotlib and Seaborn libraries are used for data visualization to gain insights and understand the relationships between variables.
- **Machine Learning Algorithms**: Implemented nine machine learning algorithms including Random Forest, SVM, XGBoost, and GradientBoost using Scikit-learn.
- **MLflow Integration**: MLflow is integrated for experiment tracking and logging, allowing for easy comparison of model performance and parameter tuning.
- **DVC Usage**: Data Version Control (DVC) is used for pipeline tracking, ensuring reproducibility and versioning of data, models, and experiments.
- **Prediction Pipeline**: A prediction pipeline is created to streamline the process of loading data, preprocessing, and making predictions using trained models.
- **Flask Web App**: A Flask web application is developed to provide a user-friendly interface for interacting with the model. Users can input student data and get predictions on student performance.
- **Docker Integration**: Docker is integrated for containerization, enabling consistent deployment across different environments.
- **CI/CD Deployment**: GitHub Actions is used for continuous integration and continuous deployment (CI/CD) pipeline. Changes pushed to the repository trigger automated testing and deployment to AWS.
