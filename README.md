# Logistic Regression – Scratch vs Sklearn

## Overview
This project explores logistic regression from scratch using NumPy and compares it with sklearn’s implementation. It includes training, prediction, visualization, and performance analysis.

## Files
- `manual_logistic_regression.py`: Logistic regression built from scratch  
- `sklearn_logistic_regression.py`: Sklearn implementation and comparison  
- `visualization_analysis.py`: Decision boundaries, confusion matrices, and classification reports  
- `visuals/`: Saved plots (sigmoid curve, decision boundaries)  
- `model_evaluation.ipynb`: Evaluation notebook with metrics and visualizations

## Reflection
Building the model manually helped me understand how gradient descent works and how predictions are formed. Sklearn is faster and optimized, but coding it myself made me think like an engineer, not just a tool user.

## Dataset
Simple binary classification using student exam scores and study hours.

## Requirements
- Python  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## Model Evaluation Summary

This section summarizes how I evaluated my logistic regression model using multiple metrics and visualizations.

### Metrics Explained
- **Accuracy**: Measures how often the model predicts correctly overall.
- **Precision**: Out of all predicted positives, how many were actually correct.
- **Recall**: Out of all actual positives, how many did the model correctly identify.
- **F1 Score**: Combines precision and recall into one balanced metric.
- **AUC (Area Under Curve)**: Measures how well the model separates the classes.

### Visualizations
- **Confusion Matrix**: Shows correct and incorrect predictions for each class.
- **ROC Curve**: Displays the trade-off between true positive rate and false positive rate.

### Class Imbalance Test
I tested the model on an imbalanced dataset (80% class 0, 20% class 1).  
Even though accuracy was 80%, precision, recall, and F1 Score dropped to 0.  
This shows why accuracy alone can be misleading.

### Screenshots / Results
All metric outputs and plots are included in:  
**`model_evaluation.ipynb`**
