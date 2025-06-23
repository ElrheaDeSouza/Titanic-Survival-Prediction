# 🚢 Titanic Survival Prediction System

A machine learning project that predicts passenger survival on the RMS Titanic using historical data and advanced classification algorithms.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)


## 🎯 Overview

The Titanic Survival Prediction System uses machine learning to analyze passenger data from the famous 1912 Titanic disaster and predict whether a passenger would have survived. This project demonstrates data preprocessing, feature engineering, model training, and evaluation techniques commonly used in classification problems.

### Key Objectives
- Predict passenger survival with high accuracy
- Identify the most important factors affecting survival
- Provide insights into historical patterns and demographics
- Demonstrate end-to-end machine learning workflow

## ✨ Features

- **Multiple ML Algorithms**: Comparison of various classification models
- **Data Preprocessing**: Comprehensive data cleaning and feature engineering
- **Feature Analysis**: Detailed exploration of factors affecting survival
- **Model Evaluation**: Cross-validation and performance metrics
- **Prediction Interface**: Easy-to-use prediction functionality
- **Model Persistence**: Save and load trained models

### Dependencies

```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
plotly>=5.0.0
```

### Feature Importance

The most influential factors for survival prediction:

1. **Sex** (0.32) - Gender was the strongest predictor
2. **Fare** (0.24) - Higher fare correlated with better survival
3. **Age** (0.18) - Younger passengers had higher survival rates
4. **Pclass** (0.15) - First-class passengers survived more often
5. **Embarked** (0.11) - Port of embarkation showed patterns

## 🔬 Methodology

### 1. Data Preprocessing
- Handle missing values using statistical imputation
- Extract features from names (titles, family size)
- Encode categorical variables
- Scale numerical features
- Create interaction features

### 2. Feature Engineering
- **Family Size**: SibSp + Parch + 1
- **Title Extraction**: Extract titles from names (Mr, Mrs, Miss, etc.)
- **Fare Binning**: Group fares into categories
- **Age Groups**: Categorize ages into meaningful groups
- **Deck Information**: Extract deck from cabin numbers

### 3. Model Training
- Cross-validation for robust evaluation
- Hyperparameter tuning using GridSearchCV
- Ensemble methods for improved performance
- Feature importance analysis


## 🐛 Known Issues

- Some cabin information is missing and could be better imputed
- Model performance could be improved with more advanced feature engineering
- Need to add more comprehensive error handling

## 🙏 Acknowledgments

- **Kaggle** for providing the Titanic dataset
- **Scikit-learn** community for excellent documentation
- **Pandas** and **NumPy** for data manipulation tools
