# Logistic Regression Classification

This Jupyter Notebook (`logestic_reg.ipynb`) demonstrates binary classification using logistic regression with hyperparameter tuning and evaluation.

## Contents

- **Synthetic Data Generation:**  
  Uses `make_classification` from scikit-learn to create a binary classification dataset.

- **Data Splitting:**  
  Splits data into training and test sets.

- **Model Building:**  
  - Implements logistic regression.
  - Performs hyperparameter tuning using `GridSearchCV` with cross-validation.

- **Model Training & Evaluation:**  
  - Trains the model with best parameters.
  - Predicts test set labels.
  - Evaluates accuracy, confusion matrix, and classification report.
  - Computes ROC-AUC and plots ROC curve.
  - Demonstrates threshold adjustment for classification.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Open `logestic_reg.ipynb` in Jupyter Notebook or VS Code.
2. Run each cell step by step to generate data, train the model, and evaluate results.

## Notes

- The notebook uses synthetic data for demonstration.
- Hyperparameter tuning is performed with multiple penalties, solvers, and regularization strengths.
- Evaluation includes accuracy, confusion matrix, classification report, ROC-AUC, and ROC curve visualization.
- You can adjust the classification threshold to see its effect