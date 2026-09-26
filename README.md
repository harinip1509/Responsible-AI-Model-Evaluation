# Responsible AI & Model Evaluation

A machine learning project that evaluates a Titanic survival prediction model using responsible AI principles. The project measures classification performance, checks fairness across a sensitive attribute, and explains model predictions with SHAP.

## Features

- Random Forest classification
- Confusion Matrix visualization
- Precision, Recall & F1-Score evaluation
- Fairness analysis using **Sex** as the sensitive attribute
- SHAP global and local explainability
- Google Colab implementation

## Project Structure

```text
responsible-ai-evaluation/
│── notebooks/
│   └── 01_model_evaluation.ipynb
│── reports/
│   └── shap_summary.png
│── README.md
```

## Technologies Used

- Python 3.10
- Google Colab
- Scikit-learn
- Pandas
- Seaborn & Matplotlib
- SHAP

## Output

The notebook generates:

- Confusion Matrix
- Classification Report
- Accuracy, Precision, Recall & F1-Score
- Bias/Fairness Report
- SHAP Summary Plot
- SHAP Waterfall Plot

## Author

Harini P
