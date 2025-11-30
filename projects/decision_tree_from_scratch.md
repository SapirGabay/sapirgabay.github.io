---
layout: default
title: "Decision Tree from Scratch: Bank Customer Deposit Prediction"
---

## 🧠 Project: Decision Tree Implementation and Statistical Pruning

## Project Summary

This project demonstrates deep expertise in core Machine Learning architecture by implementing a complex classification model from scratch (without scikit-learn), validated through advanced statistical methods.

## 🎯 The Challenge (Challenge)

To build an accurate and interpretable non-parametric model capable of predicting bank customer subscription to a term deposit (the 'y' variable) while overcoming the inherent bias of high-cardinality features in standard Information Gain metrics.

## ⚙️ The Action (Action)

* **Model Implementation:** Developed the **Decision Tree Classifier entirely from scratch** in Python, including the recursive build logic.
* **Feature Selection:** Used a **Modified Gain Ratio** criterion for node splitting to ensure fair feature selection and minimize bias towards features with many unique values.
* **Data Preprocessing:** Implemented **K-Means Clustering (custom)** to effectively categorize continuous numerical features (Age, Balance, Duration) into discrete, actionable groups.
* **Statistical Validation:** Applied **Chi-Squared Pruning ($\chi^2$)** to post-prune the tree, enhancing generalizability and preventing overfitting.
* **Evaluation:** Validated model stability and performance using **K-Fold Cross-Validation** (as defined in `tree_error` function).

## ✅ The Result (Result)

The final model provides a highly **interpretable decision path** for the bank, enabling clear identification of customer segments most likely to subscribe. The custom implementation and rigorous validation process (Modified Gain Ratio, $\chi^2$ Pruning) showcase strong command of core AI algorithms and data structure methodologies.

---

[**View Code and Full Documentation on GitHub**](https://github.com/SapirGabay/AI_Projects)
