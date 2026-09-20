# Bank Marketing — Term Deposit Subscription Analysis

A machine-learning and exploratory-analysis project examining which client and campaign characteristics are associated with **term-deposit subscription**.

## Project objective

The work explores the bank-marketing problem from two angles:

1. understand client/campaign patterns through exploratory analysis, and
2. prepare and compare classification approaches for predicting subscription.

## Repository contents

```text
Bank-Marketing-dataset/
├── Bank Marketing Dataset.ipynb
├── Bank Marketing Dataset_Milestone_2.ipynb
├── df_X.csv
├── df_y.csv
├── info.csv
├── PROJECT_STATUS.md
├── LICENSE
└── README.md
```

The repository is currently notebook-based; it does not contain a production application or model-serving API.

## Workflow covered

- dataset inspection
- missing-value handling
- categorical encoding
- numerical scaling
- exploratory data analysis
- train/test preparation
- classification modelling

The existing milestone work references models such as Logistic Regression, Random Forest, and Gradient Boosting/XGBoost-style approaches. Metric values should be taken from the executed notebooks rather than invented in the README.

## Important modelling note

Features such as call duration can create unrealistic predictive performance if they are only known after the marketing interaction has taken place. For a real pre-call decision model, such leakage-prone variables should be excluded or clearly separated from retrospective analysis.

## Tools

Python · Pandas · Scikit-learn · Jupyter Notebook

## Run

Open the notebooks in Jupyter/VS Code and keep `df_X.csv`, `df_y.csv`, and `info.csv` available in the repository root unless the notebook paths are later refactored.

## Deployment

No deployment is required for this version. The current deliverable is a notebook-based analysis/modelling project.

## API integration

None.

## Portfolio role

This is an earlier ML project. It is useful as evidence of progression, but it should remain unpinned while newer financial-risk and fraud projects lead the portfolio.

## Next improvements

- consolidate the two milestone notebooks into one clean final notebook
- verify and publish final evaluation metrics
- document the exact source/schema of the dataset
- turn preprocessing + modelling into a reproducible Scikit-learn Pipeline
- add a compact requirements.txt
- only build a prediction app if the final model/input contract is worth demonstrating
