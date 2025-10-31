## Name: Om Vijay Shende
## Roll No: CE22B083

--Assignmen 7.ipynb: Contain the notebook that performs multi-class model selection using ROC and Precision-Recall curves, focusing on a land cover classification task.
-- README.md : Contains detailed information related to this repository

***

# Assignment 7: Multi-Class Model Selection Using ROC and PR Curves


## Features

- Loads and prepares a UCI land cover dataset.
- Implements preprocessing (standardization, class label remapping, train/test split).
- Compares multiple classifiers:
  - KNN
  - Decision Tree
  - Gaussian Naive Bayes
  - Logistic Regression
  - SVC (RBF)
  - Random Forest
  - XGBoost
  - Dummy baselines (prior/constant)
- Evaluates models using:
  - Accuracy and Weighted F1-Score
  - Macro-Averaged ROC curve and AUC
  - Macro-Averaged Precision-Recall curve and Average Precision
- Makes model recommendations based on quantitative and visual analysis.

## Usage

1. Open `Assignmen-7.ipynb` in Jupyter Notebook.
2. Run all cells sequentially.
3. Inspect output tables and charts for performance comparisons and recommendations.

## Requirements

- Python 3.x
- scikit-learn
- xgboost
- pandas, numpy, matplotlib, seaborn

## Outputs

- Prints accuracy, F1, ROC AUC, Average Precision for all models.
- Plots ROC and Precision-Recall curves for model comparison.
- Recommends the best model for multi-class land cover prediction.
