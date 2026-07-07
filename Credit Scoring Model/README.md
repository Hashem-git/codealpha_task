# Credit Scoring Model - CodeAlpha Internship Task 1

## Project Objective
The goal of this project is to build a robust Machine Learning classification model to predict an individual's creditworthiness (Credit Scoring) using historical financial records.

## Approach & Methodology
1. **Data Preprocessing & Cleaning**: Handled missing financial records via median imputation.
2. **Feature Engineering**: Extracted critical risk indicators including **Debt-to-Income (DTI) Ratio** and **Income-per-Account**.
3. **Model Selection**: Trained a **Random Forest Classifier** (100 decision trees) to split non-linear credit risk boundaries.
4. **Data Splitting**: 80% Training set and 20% Testing set using stratified sampling.

## Evaluation Results
- **General Accuracy**: 97.00%
- **Good Credit Precision**: 98%
- **Good Credit Recall**: 98%
- **ROC-AUC Score**: 0.9833

## Technologies Used
- Python 3
- Pandas & NumPy
- Scikit-Learn
- Matplotlib & Seaborn
