# Customer Churn Analysis

This project analyzes customer churn behavior using R and R Markdown. It identifies behavioral churn signals, builds predictive models, and translates the results into retention-focused business recommendations.

## What This Project Contains

- `Customer Churn Analysis.Rmd`: Source analysis with data loading, feature engineering, exploratory analysis, model training, and evaluation.
- `Customer-Churn-Analysis.html`: Rendered report with embedded charts, model output, and narrative interpretation.
- `customer_churn_csv.csv`: Dataset used by the R Markdown workflow.

## Business Question

Which customer behaviors and account characteristics are most associated with churn risk, and how can those patterns support retention prioritization?

## Analytical Approach

- Created a churn label from tenure, usage frequency, support interactions, and payment delay behavior.
- Explored churn patterns across contract length and subscription type.
- Trained logistic regression and decision tree models using a train-test split.
- Evaluated model performance with confusion matrix metrics and ROC-AUC.
- Identified high-risk customer segments for targeted retention action.

## Tools Used

R, R Markdown, tidyverse, ggplot2, caret, rpart, rpart.plot, knitr.

## Reproducibility Note

The R Markdown file now uses the relative file path `customer_churn_csv.csv`, so the analysis can be rerun from the repository root without relying on a local machine path.
