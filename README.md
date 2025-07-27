#  Heart Disease Prediction: Stacked Ensembles and Causal Feature Selection

This project explores advanced machine learning techniques for predicting heart disease. It includes both the reproduction of a published ensemble-learning approach and the design of an original ML solution incorporating causal feature selection and stability strategies.

## Objectives

- Replicate the results of a published ML study on heart disease prediction
- Build ensemble models including stacking, voting, and boosting classifiers
- Apply novel feature selection methods using causal inference and stability selection
- Improve model interpretability and generalization

---

## Project Structure

### Part 1 — Reproducing a Research Paper
- Models Implemented:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - K-Nearest Neighbors
  - XGBoost
  - Stacking Classifier
- Evaluation:
  - Accuracy, Precision, Recall, F1-score
  - Cross-validation performance
  - Comparison with published metrics

### Part 2 — Original Contribution
- Introduces **Causal Discovery** and **Stability Selection** for feature selection
- Custom pipeline improves:
  - Generalization (cross-validation and test performance)
  - Interpretability (through cleaner feature sets)
  - Robustness (using stratified splits and calibration)

---

## Techniques & Tools

- Python (3.9+)
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `xgboost`
- Ensemble learning (Stacking, Voting)
- Feature selection (RFE, permutation importance)
- Causal feature discovery (manual logic or external library)
- Model calibration and cross-validation

---

## Evaluation Metrics

- Accuracy, Precision, Recall, F1-score
- Confusion Matrices
- Cross-validation consistency
- Performance comparison between baseline and custom pipeline

---

## Key Skills Demonstrated

- Reproducible ML research
- Ensemble learning (stacked models)
- Feature selection with interpretability focus
- Model comparison and evaluation
- Data preprocessing and pipeline construction

---

## Author

**Sehar Aejaz**  
seharaejaz@gmail.com  

---

## Summary

This project highlights the complete workflow of both replicating research and contributing original improvements in the medical ML domain. The use of stacked models, causal reasoning, and thoughtful evaluation makes it a strong demonstration of applied machine learning and research literacy.

