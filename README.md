# Predicting chance of Dropout within the MNCH continuum in Kenya using Machine Learning

This repository contains the code and data for a research project comparing various machine learning models to predict dropout rates from the MNCH continuum in Kenya. The study aims to identify the most accurate model for early intervention and improved health outcomes.

## Objectives

- Compare various machine learning models in predicting dropout rates from MNCH continuum.
- Identify the most accurate model to enhance early intervention strategies and health outcomes.

## Methods

- Evaluated multiple machine learning models.
- Compared performance metrics including accuracy, precision, recall, and F1-score.
- Visualized results using confusion matrices and ROC curves.

## Results

The XGBoost model demonstrated superior performance with the following results:

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.86      | 0.93   | 0.90     | 5134    |
| 1     | 0.98      | 0.97   | 0.97     | 7975    |
| 2     | 0.94      | 0.88   | 0.91     | 5101    |
| 3     | 0.98      | 0.98   | 0.98     | 7918    |

**Overall Accuracy:** 0.95 (across 26128 samples)

## Conclusions

The study’s findings identified XGBoost as the most reliable model for predicting ANC dropouts. Implementing this model can significantly enhance early intervention strategies, ultimately improving health outcomes for mothers and newborns in Kenya. This research underscores the transformative potential of machine learning in public health, particularly in the context of maternal and child health.

## Visualizations

Included visualizations:
- Confusion Matrices
- ROC Curves

## Repository Structure

- `code/`: Contains the scripts for data preprocessing, model training, and evaluation.
- `data/`: Contains the dataset used for the study.
- `results/`: Contains the visualizations and output metrics.

