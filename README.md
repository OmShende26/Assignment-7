## Name: Om Vijay Shende
## Roll No: CE22B083

Assignment-7 Repository
│
├── Assignmen 7.ipynb
│   └── Notebook for multi-class model selection with ROC and Precision-Recall curves on land cover data
│
└── README.md
    └── Detailed information about the repository


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
