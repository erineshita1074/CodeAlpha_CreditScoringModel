# Credit Scoring Model

## CodeAlpha Machine Learning Internship — Task 1

## Objective
Predict an individual's creditworthiness (good/bad credit risk) using past financial data, applying classification algorithms.

## Dataset
**UCI German Credit Data**
- 1000 samples, 20 features (checking account status, credit history, purpose, credit amount, employment history, age, housing, job, etc.)
- Target: Binary classification (0 = Good credit, 1 = Bad credit)
- Source: https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

## Approach
1. Loaded and explored the dataset, checked class distribution
2. Encoded categorical features using Label Encoding
3. Scaled numeric features using StandardScaler
4. Split data into train (80%) and test (20%) sets with stratification
5. Trained three classification models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
6. Evaluated models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
7. Visualized results with confusion matrices, ROC curves, and feature importance

## Key Features Used
Financial history, income indicators, existing credits, employment duration, age, housing status, and loan purpose.

## Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.765 | 0.627 | 0.533 | 0.577 | 0.790 |
| Decision Tree | 0.730 | 0.571 | 0.400 | 0.471 | 0.724 |
| Random Forest | 0.770 | 0.706 | 0.400 | 0.511 | 0.813 |

**Best Model: Random Forest** — achieved the highest Accuracy (77%) and ROC-AUC (0.813), indicating the best overall ability to distinguish between good and bad credit risk.

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
Open `CodeAlpha_CreditScoringModel.ipynb` in Jupyter Notebook or Google Colab and run all cells sequentially.

## Project Structure
- CodeAlpha_CreditScoringModel.ipynb — main notebook with code, training, and results
- README.md — project documentation

## Author
Eshita — Final Year Software Engineering Student, Daffodil International University
