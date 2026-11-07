# Housing Price Prediction: Multiple Linear Regression

Models property prices for a real-estate company in the Delhi region and identifies which features drive price.

## Problem

The company wants to know which variables affect house prices (area, bedrooms, bathrooms, parking and others), to relate price to them with an interpretable linear model, and to know how well the model predicts.

## Approach

1. Explore numeric and categorical variables
2. Create dummy variables, split train/test, rescale features
3. Build the model step by step, starting with area (R² 0.283), then adding bathrooms (adjusted R² 0.477) and bedrooms, then all variables
4. Remove variables using VIF and p-values over several rounds
5. Residual analysis of the training data
6. Predict on the test set with the final model

## Results

- Training adjusted R² of the final models is about 0.67
- Test R² of the final model: 0.66

## Files

| File | Purpose |
| --- | --- |
| `Housing+Case+Study+--+Tree+Models.ipynb` | Full analysis |

## Stack

Python, pandas, scikit-learn, statsmodels, matplotlib, seaborn
