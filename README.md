# EL-Internship-Task-AI-ML-4

## Task Overview
This project is part of the AI & ML Internship – Task 4, focusing on binary classification using **Logistic Regression**. The goal is to build a model that can classify whether a tumor is malignant or benign based on features in the Breast Cancer Wisconsin Dataset.

## Dataset
- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Source:** [Kaggle ](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target Variable:** `diagnosis` (M = Malignant, B = Benign)
- **Type:** Binary Classification

## Technologies Used
- Python 
- Pandas & NumPy 
- Scikit-learn 
- Matplotlib & Seaborn
- [Google Colab](https://colab.research.google.com/drive/1OpnK4ShpBdDGz36CbW2sza4-wMmmVonN?usp=sharing)

## Steps Performed

1. **Data Loading and Cleaning**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Converted categorical labels to binary (`M` → 1, `B` → 0)

2. **Preprocessing**
   - Feature standardization using `StandardScaler`
   - Splitting into training and test sets

3. **Modeling**
   - Applied **Logistic Regression** using Scikit-learn
   - Trained on 80% data, tested on 20%

4. **Evaluation Metrics**
   - **Confusion Matrix**
   - **Precision, Recall, F1-score**
   - **ROC-AUC Curve**
   - Tested different thresholds

5. **Visualization**
   - Plotted sigmoid function to understand logistic behavior
   - Plotted ROC curve to assess model performance

## Evaluation Results

| Metric        | Value   |
|---------------|---------|
| Accuracy      | 97%     |
| Precision     | 95%     |
| Recall        | 98%     |
| ROC-AUC Score | 0.99    |

> Results may vary slightly depending on train-test split.

## Key Learnings
- Difference between Linear and Logistic Regression
- Importance of evaluation metrics like ROC-AUC, Precision, Recall
- Behavior of the sigmoid function in classification tasks
- How adjusting the threshold affects predictions

## Files in Repository
- `logistic_regression_breast_cancer.ipynb` — Jupyter notebook with full implementation
- `README.md` — GitHub cover page
- `sigmoid_plot.png` (optional) — Visualization of the sigmoid curve
- `roc_curve.png` (optional) — ROC curve of the model

## Author
**Dhanush G**  
dhanushg0710@gmail.com  
[LinkedIn](https://www.linkedin.com/in/dhanush-g-805492345)  
