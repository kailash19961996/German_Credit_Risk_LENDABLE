# German Credit Data Analysis

## Overview

This project analyzes the [German Credit Data](https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29) to build a predictive model that assesses the creditworthiness of individuals. The dataset includes 1,000 instances, each with 20 attributes, and classifies individuals as having either good or bad credit risk.

## Dataset Description

The dataset comprises 20 attributes, including:

- **Status of existing checking account**: Categorical
- **Duration in month**: Numerical
- **Credit history**: Categorical
- **Purpose**: Categorical
- **Credit amount**: Numerical
- **Savings account/bonds**: Categorical
- **Present employment since**: Categorical
- **Installment rate in percentage of disposable income**: Numerical
- **Personal status and sex**: Categorical
- **Other debtors / guarantors**: Categorical
- **Present residence since**: Numerical
- **Property**: Categorical
- **Age in years**: Numerical
- **Other installment plans**: Categorical
- **Housing**: Categorical
- **Number of existing credits at this bank**: Numerical
- **Job**: Categorical
- **Number of people being liable to provide maintenance for**: Numerical
- **Telephone**: Categorical
- **Foreign worker**: Categorical

The target variable indicates credit risk: **1** for good credit and **2** for bad credit.

## Project Objectives

- **Data Preprocessing**: Handle missing values, encode categorical variables, and normalize numerical features.
- **Exploratory Data Analysis (EDA)**: Understand the distribution of variables and identify patterns or correlations.
- **Model Development**: Train and evaluate various classification models to predict credit risk.
- **Model Evaluation**: Assess models using appropriate metrics and select the best-performing model.
- **Cost-Sensitive Analysis**: Incorporate the provided cost matrix to evaluate the financial implications of misclassifications.

## Cost Matrix

The dataset includes a cost matrix to penalize misclassifications:

| Actual / Predicted | Good (1) | Bad (2) |
|--------------------|----------|---------|
| Good (1)           | 0        | 1       |
| Bad (2)            | 5        | 0       |

Misclassifying a bad credit risk as good incurs a higher cost, emphasizing the importance of accurate predictions.

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/german-credit-analysis.git