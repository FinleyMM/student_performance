# K-Nearest Neighbours (KNN) and Support Vector Machine (SVM) Classifier on Student Grades Dataset

This project implements classification models (KNN and SVM) to predict student final grades (`G3`) based on their first two grading periods (`G1` and `G2`). The dataset is preprocessed, models are trained and evaluated, and results are visualised. Hyperparameter tuning is performed to optimise KNN performance.

## Project Overview

- **Data Preprocessing:** Selected features (`G1`, `G2`), scaled using `StandardScaler`.
- **Models Used:** K-Nearest Neighbours (KNN), Support Vector Machine (SVM).
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1 Score.
- **Visualisations:** Decision boundary for KNN, performance comparison bar plot, confusion matrix.
- **Hyperparameter Tuning:** Grid search to find best KNN parameters.
