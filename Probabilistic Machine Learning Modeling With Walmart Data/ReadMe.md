# Probabilistic Machine Learning for Walmart Sales Prediction

## Project Overview
This project applies **probabilistic machine learning (ProbML)** techniques to analyze and forecast **Walmart sales data**. The goal is to leverage **Bayesian modeling** using **PyMC** to estimate uncertainties in sales predictions and provide robust insights into sales patterns.

## Key Features
- **Dataset**: Walmart sales dataset with preprocessing steps.
- **Probabilistic Modeling**: Uses Bayesian inference for robust forecasting.
- **Data Preprocessing**: Handles missing values and feature selection.
- **Statistical Analysis**: Computes means, variances, and distributions of key sales metrics.

## Installation
Ensure you have the required dependencies installed before running the notebook:

```bash
pip install numpy pandas seaborn scipy pymc3 arviz
```

## How to Run
1. Clone this repository and navigate to the project folder:
    ```bash
    git clone <repository_url>
    cd <project_folder>
    ```
2. Open the Jupyter Notebook and run the cells sequentially:
    ```bash
    jupyter notebook ProbMLWalmart.ipynb
    ```

## Implementation Details
- **Data Preprocessing**:
  - Dropped irrelevant columns (`Payment_Method`, `Location`, `Season`).
  - Handled missing values and standardized data.
- **Bayesian Modeling**:
  - Utilizes PyMC for probabilistic forecasting.
  - Implements prior distributions and posterior inference.
- **Evaluation Metrics**:
  - Visualizes predictive distributions.
  - Uses `ArviZ` for Bayesian model diagnostics.

## Results
The project demonstrates the effectiveness of **Bayesian machine learning** in handling sales prediction with uncertainty estimation, offering insights into **sales trends and variations**.

## Author
- **Sanika Dhayabar Patil**
