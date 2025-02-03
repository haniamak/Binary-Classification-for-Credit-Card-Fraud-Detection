# Binary-Classification-for-Credit-Card-Fraud-Detection
## Training and Evaluating models for [credit card fraud detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), a highly unbalanced dataset.

# Models Trained:
- Logistic Regresion
- Random Forest
- K Nearest Neighbors
- XGBoost

# Techniques Used:
- Stratified Split
- Polynomial Features
- SMOTE

# Final Scores:
| Model | True Negatives | False Positives | False Negatives | True Positives | Pecision | Recall | F-1 | Accuracy |
|-------|----------------|-----------------|-----------------|----------------|----------|--------|-----|----------|
| Logistic Regression | 56850 | 13 | 36 | 63 | 0.828947 | 0.636364 | 0.720000 | 0.999140 |
| Random Forest | 56855 | 8 | 18 | 81 | 0.910112 | 0.818182 | 0.861702 | 0.999544 |
| KNN | 56690 | 173 | 74 | 25 | 0.126263 | 0.252525 | 0.168350 | 0.995664 |
| XGBoost | 56856 | 7 | 19 | 80 | 0.919540 | 0.808081 | 0.860215 | 0.999544 |
