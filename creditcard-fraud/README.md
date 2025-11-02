# Credit Card Fraud Detection

This project explores machine learning methods for detecting fraudulent credit card transactions, using a real-world dataset with a strong class imbalance. The goal is to compare multiple classification algorithms and evaluate their ability to identify fraud while minimizing false positives.

---

## Project Overview

Credit card fraud detection is a classic binary classification problem where fraudulent transactions are rare but costly.  
This project applies supervised learning models to predict whether a given transaction is fraudulent based on anonymized features.

---

## Models Implemented

| Model | Description | Status |
|-------|--------------|--------|
| **Decision Tree** | Baseline model to understand feature splits and interpretability | Completed |
| **K-Nearest Neighbors (KNN)** | Distance-based classifier to explore local decision boundaries | In Progress |
| **Logistic Regression** | Linear model to evaluate probabilistic predictions | Planned |


---
## Current Results

| Metric | Decision Tree |
|---------|----------------|
| Accuracy | *99.87%* |
| Precision | *95.52%* |
| Recall | *81.01%* |

*(To be updated as additional models are implemented.)*

---

## Key Learnings

- Handling **imbalanced datasets** is critical (fraud cases are rare).  
- Decision trees provide **interpretability**, but may overfit.  
- Would love to test other models in the future such as Random Forests, XGBoost, and Neural Networks for comparison.

---
