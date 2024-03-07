# Ensemble Models Analysis - CA04

## Data Source and Contents

This project uses a dataset from the Census Bureau, comprising salaries and seven demographic variables to predict income classes '>50K' and '<=50K'. The dataset includes 48,842 instances and is pre-split into "Training" and "Testing" sets.

**Dataset Path:** [Census Data CSV](https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true)

## Objective

The goal is to analyze the performance of ensemble methods such as Random Forest, AdaBoost, Gradient Boost, and XGBoost in predicting income levels.

## Procedures

- **Optimal Hyperparameter Determination:**
  Evaluate Accuracy and AUC metrics to determine the best number of estimators.
  
- **Model Training and Evaluation:**
  Train the specified ensemble models and assess their performance through visualizations.

- **Performance Comparison:**
  Document and compare the best Accuracy and AUC scores in a structured table.

## Deliverables

- A fully functional Jupyter Notebook.
- A comprehensive README file detailing the methodology and results.
- Repository access on GitHub containing the notebook and README.

## Observations

The analysis will include insights on the behavior of classifiers with varying numbers of estimators and identify the optimal count of estimators.

## Useful Resources

- [SKlearn Model Evaluation Functions](https://scikit-learn.org/stable/modules/model_evaluation.html)

