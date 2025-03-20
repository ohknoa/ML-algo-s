# Linear-Regression-Scratch

## Overview
- **Algorithm**: Ordinary Least Squares using normal equation \( \theta = (X^T X)^{-1} X^T y \).
- **Features**: Handles single or multi-feature \( X \).

## How It Works
1. **Input**: \( X \) (features) and \( y \) (target).
2. **Bias**: Adds a column of ones to \( X \) in the front for intercept.
3. **Fit**: Solves \( \theta \) directly, splits into weights (\( w \)) and bias (\( b \)).
4. **Predict**: Computes \( X @ w + b \) for multi-feature support.

## Usage
- Open `LR_OLS.ipynb` in Google Colab.
- Run the cells to see it match sklearn on sample data.
- Swap in your own dataset to test.

## Results
- Tested with the “Linear Regression” dataset by Vahe Andonians from Kaggle.
- Matches sklearn: `coef_` and `intercept_` align within floating-point precision—see `LR_OLS.ipynb` for exact values.

## Why This?
- Built to understand the behind-the-scenes of sklearn and how linear regression works with multi-features.

---
*March 20, 2025 - Coded from scratch.*
