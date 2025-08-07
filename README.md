# Linear Regression Project

This Jupyter Notebook (`linear_regression.ipynb`) demonstrates both simple and multiple linear regression using the scikit-learn library.

## Contents

- **Data Loading & Exploration:**  
  Loads `dataset.csv`, checks for missing values, and explores basic statistics.

- **Simple Linear Regression:**  
  - Predicts `price` using `area` as the feature.
  - Splits data into training and test sets.
  - Standardizes the feature.
  - Fits a linear regression model.
  - Visualizes the regression line.
  - Evaluates performance using MAE, MSE, RMSE, and R² score.

- **Multiple Linear Regression:**  
  - Uses `area`, `bedrooms`, `bathrooms`, and `stories` as features to predict `price`.
  - Splits and standardizes data.
  - Fits and evaluates the model.
  - Visualizes predictions and residuals.

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

1. Place `dataset.csv` in the project directory.
2. Open and run `linear_regression.ipynb` in Jupyter Notebook or VS Code.
3. Follow the notebook cells for step-by-step regression analysis.

## Notes

- The notebook prints model coefficients and intercepts.
- Performance metrics and plots help assess model accuracy.
- You can modify features and target variables as needed for# linear_regression
