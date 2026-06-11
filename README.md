# Exoplanet Classification Using Machine Learning

## Overview

This project focuses on the classification of exoplanets based on their physical and orbital characteristics using machine learning techniques. The rapid growth in the number of discovered exoplanets creates a need for automated analysis methods capable of identifying and categorizing different planet types.

The objective of this project is to predict the Planet Type of confirmed exoplanets using data from the NASA Exoplanet Archive Intelligence dataset.

## Dataset

Source: NASA Exoplanet Archive Intelligence Dataset

Kaggle:
https://www.kaggle.com/datasets/kanchana1990/nasa-exoplanet-archive-intelligence

Data source:
NASA Exoplanet Archive

Object of study:
Confirmed exoplanets

Target variable:
Planet Type

## Project Objectives
- Explore the structure of the dataset and identify the target variable.
- Perform exploratory data analysis (EDA) and visualize key relationships.
- Prepare and preprocess the data for machine learning.
- Split the dataset into training and testing sets.
- Train multiple machine learning models for exoplanet classification.
- Compare model performance using classification metrics.
- Identify the most suitable model for predicting exoplanet types.

## Machine Learning Models

The following classification algorithms were implemented and evaluated:

- Logistic Regression
- Gradient Boosting Classifier
- Neural Network (MLP)

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

## Results
| Model | Accuracy | Macro F1 | Notes |
|---|---|---|---|
| Logistic Regression | 0.7723 | 0.77 | Baseline model, average performance |
| GradientBoostingClassifier | 1.0000 | 1.00 | Perfect score — requires data leakage check |
| Neural Network | 0.9187 | — | Strong result after 100 training epochs |

## Key Findings
- Logistic Regression provided a reliable baseline for comparison.
- The Neural Network achieved high classification accuracy and demonstrated strong predictive capability.
- Gradient Boosting Classifier produced perfect classification results, indicating either exceptional separability of the classes or the possibility of data leakage that requires further validation.

## Technologies
- Python
- Pandas
- Scikit-learn
- PyTorch
- Matplotlib
- Seaborn

## Repository Structure
- code/ – trained models
- presentation/ – project presentation and visualizations and results

## Future Improvements
- Investigate potential data leakage in the Gradient Boosting model.
- Perform hyperparameter optimization.
- Explore ensemble learning approaches.
- Evaluate additional deep learning architectures.

## Author

Inkara Suleimenova
