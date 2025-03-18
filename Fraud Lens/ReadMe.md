# FraudLens: Credit Card Fraud Detection

## Project Overview
FraudLens is a **credit card fraud detection system** designed to handle highly imbalanced datasets. This project leverages **machine learning techniques** to accurately identify fraudulent transactions while mitigating bias towards non-fraudulent cases.

## Key Challenges & Solutions
- **Class Imbalance**: Fraudulent transactions are rare compared to legitimate ones.
- **Handling Imbalance**: Utilizes **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset.
- **Feature Engineering**: Extracts meaningful patterns from transaction data.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook FraudLens.ipynb
    ```

## Techniques Used
- **Data Preprocessing**: Cleaning and preparing transaction data.
- **Oversampling with SMOTE**: Balancing class distribution.
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Neural Networks (optional)
- **Model Evaluation**: Precision, Recall, F1-score, and ROC-AUC analysis.

## Results
FraudLens improves fraud detection accuracy by reducing class imbalance bias, enhancing precision and recall for fraudulent transactions.

## Author
- **Sanika Dhayabar Patil**
