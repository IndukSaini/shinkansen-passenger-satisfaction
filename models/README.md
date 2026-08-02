# Saved Models

The final solution used an ensemble of five CatBoost models trained through stratified five-fold cross-validation.

The binary model files are not included in this repository because trained artifacts can be large and can be regenerated from the notebook.

Final configuration:

- Algorithm: CatBoostClassifier
- Objective: Logloss
- Evaluation metric: Accuracy
- Number of folds: 5
- Classification threshold: 0.50
- Mean cross-validation accuracy: 0.95825
