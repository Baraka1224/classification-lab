# Classification Model Comparison Lab

## Overview
This project compares three popular classification models — Logistic Regression, k-Nearest Neighbors (k-NN), and Decision Tree — using the Iris dataset. The models are evaluated based on key metrics such as accuracy, precision, recall, and F1-score.

## Dataset
- **Iris Dataset**: A classic multiclass classification dataset consisting of 150 samples of iris flowers with 4 numerical features.

## Models Used
- Logistic Regression
- k-Nearest Neighbors (k-NN)
- Decision Tree

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

All metrics were obtained using `classification_report` from `scikit-learn`.

## Results
All three models achieved 100% accuracy on the test data, due to the simplicity of the Iris dataset.

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression | 1.00     | 1.00      | 1.00   | 1.00     |
| k-Nearest Neighbors | 1.00     | 1.00      | 1.00   | 1.00     |
| Decision Tree       | 1.00     | 1.00      | 1.00   | 1.00     |

## How to Run
1. Clone the repository
2. Open `Classification_Lab.ipynb` in Jupyter Notebook or JupyterLab
3. Run all the cells
4. Export to PDF from File > Export Notebook As > PDF

## Files Included
- `Classification_Lab.ipynb` – Main notebook with code and analysis
- `Classification_Lab.pdf` – Rendered PDF version for submission
