
# Credit Scoring Model - CodeAlpha ML Internship

## Objective
Predict an individual's creditworthiness using past financial data.

## Dataset
UCI German Credit Data (1000 rows, 20 features)
Source: https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

## Approach
Applied Logistic Regression, Decision Tree, and Random Forest classifiers.
Preprocessing: label encoding for categorical features, standard scaling for numeric features.

## Results
| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.765 | 0.627 | 0.533 | 0.577 | 0.790 |
| Decision Tree | 0.730 | 0.571 | 0.400 | 0.471 | 0.724 |
| Random Forest | 0.770 | 0.706 | 0.400 | 0.511 | 0.813 |

## How to Run
1. Install requirements: `pip install pandas numpy scikit-learn seaborn matplotlib`
2. Run the notebook cell by cell in Google Colab or Jupyter
