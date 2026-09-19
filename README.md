# FinTrust Data Science Project

## Project Overview

This repository contains my Data Science contribution to the FinTrust Digital Bank Experience Lab project as part of the AnalystLab Africa Internship Programme.

FinTrust Digital Bank is a fictional digital banking organisation seeking to use customer and transaction data to better understand customer behaviour and support risk-related decision-making.

## Week 1 Focus

Week 1 focused on:

- Understanding the FinTrust business problem
- Reviewing the customer and transaction datasets
- Assessing data quality
- Evaluating `Risk_Review_Flag` as a potential machine-learning target
- Identifying candidate predictive features
- Developing initial hypotheses
- Creating an initial modelling plan
- Defining success criteria, risks, and the Week 2–4 roadmap

## Predictive Problem

The proposed machine-learning task is a binary classification problem aimed at predicting whether a transaction may require risk review using available customer and transaction information.

`Risk_Review_Flag` is a synthetic educational label and should not be interpreted as a confirmed fraud indicator.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

## Key Week 1 Observations

- The customer dataset contains 1,500 records.
- The transaction dataset contains 12,000 records.
- Customer and transaction records can be linked using `Customer_ID`.
- Some missing values were identified in transaction-related fields.
- `Risk_Review_Flag` is imbalanced, with approximately 80.4% `No` and 19.6% `Yes`.
- Future model evaluation should therefore use more than accuracy alone.

## Repository Structure

```text
fintrust-data-science/
│
├── FinTrust_Week1_Data_Science.ipynb
├── README.md
└── .gitignore
