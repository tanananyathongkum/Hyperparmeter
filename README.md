# Hyperparameter Tuning Project

## ⚠️ Important Note about Spelling

**Correct Spelling:** `hyperparameter` (with an 'r' after 'p')

**Incorrect Spellings to Avoid:**
- ❌ `hyperpameter` (missing 'r')
- ❌ `hyperparamter` (wrong order)
- ❌ `hyperparmeter` (wrong order)

The repository name unfortunately contains a typo (`Hyperparmeter`), but the code and notebook use the correct spelling `hyperparameter`.

## Project Overview

This project demonstrates and compares different hyperparameter tuning methods for Decision Tree models, specifically for heart disease classification.

## What are Hyperparameters?

**Hyperparameters** (ไฮเปอร์พารามิเตอร์) are configuration settings used to tune machine learning models. Unlike model parameters that are learned from data, hyperparameters are set before the training process begins.

### Common Hyperparameters for Decision Trees:
- `max_depth`: Maximum depth of the tree
- `min_samples_split`: Minimum samples required to split a node
- `min_samples_leaf`: Minimum samples required at leaf node
- `criterion`: Function to measure split quality (gini, entropy)
- `class_weight`: Weights for class balancing

## Hyperparameter Tuning Methods Compared

This notebook compares several hyperparameter tuning approaches:

1. **RandomizedSearchCV**: Random search over parameter space
2. **GridSearchCV**: Exhaustive search over specified parameter grid
3. **BayesSearchCV**: Bayesian optimization (requires scikit-optimize)
4. **OptunaSearchCV**: Modern optimization framework (requires optuna)
5. **HalvingRandomSearchCV**: Successive halving for faster search

## Files

- `hyperparameter.ipynb`: Main Jupyter notebook with comparison code
- `X_train_90.csv`, `y_train_90.csv`: Training data (90%)
- `X_test_10.csv`, `y_test_10.csv`: Test data (10%)

## How to Use

1. Install required packages:
```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn joblib
```

2. Optional packages for advanced tuning methods:
```bash
pip install scikit-optimize  # For BayesSearchCV
pip install optuna           # For OptunaSearchCV
```

3. Open and run `hyperparameter.ipynb` in Jupyter Notebook or JupyterLab

## Key Concepts

### Hyperparameter vs Parameter
- **Parameters**: Learned from data (e.g., weights in neural networks, split points in decision trees)
- **Hyperparameters**: Set by the user before training (e.g., learning rate, number of trees, max depth)

### Why Hyperparameter Tuning is Important
- Improves model performance
- Prevents overfitting or underfitting
- Optimizes the balance between bias and variance
- Helps achieve better generalization

## Thai Language Guide

**ภาษาไทย:**
- Hyperparameter = ไฮเปอร์พารามิเตอร์
- การปรับ Hyperparameter = Hyperparameter Tuning
- การเขียนที่ถูกต้อง: h-y-p-e-r-p-a-r-a-m-e-t-e-r (มี r หลัง p)

## Common Mistakes to Avoid

1. ❌ Writing "hyperpameter" instead of "hyperparameter"
2. ❌ Confusing parameters with hyperparameters
3. ❌ Not using cross-validation during hyperparameter tuning
4. ❌ Overfitting to the validation set through excessive tuning

## License

This project is for educational purposes.

## Author

Created for demonstrating proper hyperparameter tuning techniques and clarifying the correct spelling of "hyperparameter".

---

**Remember: The correct spelling is always `hyperparameter` with an 'r' after the 'p'!** ✅
