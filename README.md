# ML-Creditworthiness

This project focuses on predicting the creditworthiness of customers for a bank. The goal is to classify customers as creditworthy or unworthy of credit based on their records, credit history, and other features. Given the higher cost associated with misclassifying a creditworthy customer as unworthy, special attention has been given to minimizing false negatives.

## Problem Statement

A bank wants to predict the creditworthiness of its customers. It is significantly more costly for the bank to incorrectly classify a customer as creditworthy when they are actually unworthy of credit. Therefore, the model aims to minimize this risk while handling cases where information might be incomplete.

For this project, data from 1,000 representatively selected customers has been used. The dataset includes features related to credit history and customer records, with some features having missing values.

## Models Used

Several machine learning models have been employed to develop the predictive model:

- **Logistic Regression**: A statistical model that uses a logistic function to model a binary dependent variable.
- **Decision Tree**: A decision support tool that uses a tree-like graph of decisions and their possible consequences.
- **Random Forest**: An ensemble method that constructs multiple decision trees and merges their results to improve accuracy and control overfitting.

## Dataset

The dataset includes:
- Credit history
- Customer records
- Other relevant features

Note: Some features have missing values, which are handled as part of the preprocessing step.

## Getting Started

To get started with this project, clone this repository and navigate to the `ML-Creditworthiness` directory. The directory includes scripts for data preprocessing, model training, and evaluation.

```bash
git clone https://github.com/yourusername/ML-Creditworthiness.git
cd ML-Creditworthiness
