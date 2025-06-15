# Project Overview

The goal of this project is to **predict whether a bank customer will subscribe to a term deposit** based on their demographic and financial characteristics. The solution leverages several machine learning models, including Logistic Regression, Random Forest, and Boosting algorithms.

---

## Main Steps

1. **Data Preparation**
    - Data cleaning, encoding categorical features, and creating new useful features.

2. **Model Training**
    - Building a baseline Logistic Regression model.
    - Comparing performance with more complex models such as Random Forest and Boosting.
    - Hyperparameter tuning for model optimization.

3. **Model Evaluation**
    - The main evaluation metric is the **AUC Score** (measuring classification quality).
    - The **confusion matrix** is used for detailed error analysis.

4. **Visualization & Interpretation**
    - Analyzing feature importance and interpreting model results.

---

## Dataset

The dataset is sourced from the **UCI Machine Learning Repository** and contains information about direct marketing campaigns (phone calls) by a Portuguese bank. It includes:

- **Demographic data** (age, job, education, marital status, etc.)
- **Contact history** with the bank
- **Economic indicators**
- **Target variable:** whether the client subscribed to a term deposit (`yes`/`no`)

---

## Practical Value

- Helps the bank identify which clients are most likely to subscribe to a term deposit.
- Optimizes marketing campaign costs.
- Increases the effectiveness and conversion rate of marketing efforts.
