# Crop Recommendation System

## Project Overview
This Jupyter notebook implements a machine learning model to recommend optimal crops based on soil characteristics and climatic conditions using various machine learning algorithms. The dataset used has been downloaded from Kaggle.

## Data Analysis
The dataset includes features such as Nitrogen, Phosphorus, Potassium levels, temperature, humidity, pH, and rainfall. Initial data exploration involves checking data completeness, descriptive statistics, and distribution analysis through histograms and pair plots.

## Feature Engineering
New features like nutrient ratios and categorical seasonal features were created to enhance model training.

## Machine Learning Models and Performance
- **Random Forest**: Achieved an F1 Score of 0.99. This model demonstrated high accuracy and robust performance across various metrics.
- **Support Vector Machine (SVM)**: Reached an F1 Score of 0.97.
- **XGBoost**: Showed an F1 Score of 0.98.
- **Multi-layer Perceptron (MLP)**: Obtained an F1 Score of 0.95.
- **Logistic Regression**: Secured an F1 Score of 0.97.

## Hyperparameter Tuning
Detailed hyperparameter tuning was conducted for each model using techniques like GridSearchCV to find the optimal settings, significantly improving model accuracy.

- **Random Forest**: Achieved an F1 Score of 0.99.
- **Support Vector Machine (SVM)**: Reached an F1 Score of 0.98.
- **XGBoost**: Showed an F1 Score of 0.99.
- **Multi-layer Perceptron (MLP)**: Obtained an F1 Score of 0.96.
- **Logistic Regression**: Secured an F1 Score of 0.97.

## Technologies Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn for data visualization
- Scikit-Learn, XGBoost for machine learning
- Jupyter Notebook for implementation

## Model Evaluation
Models were evaluated based on accuracy, precision, recall, and F1 Score, with Random Forest performing the best overall.
