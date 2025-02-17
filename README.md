# Prediction of Metal Ion Content using KNN Regression

This project applies **K-Nearest Neighbors (KNN) Regression** to predict the concentration of metal ions, including **total metal concentration (c_total), Cadmium (Cd), and Lead (Pb)**, using **Euclidean distance** as the metric.

## Objective

- Predict **c_total, Cd, and Pb** concentrations using **KNN Regression**.
- Evaluate models using **Leave-One-Out Cross-Validation (LOO-CV)**.
- Implement **Leave-Replicas-Out Cross-Validation (LRO-CV)**.
- Calculate the **C-Index** for each output to assess model performance.

## Methodology

- **KNN Regression:**  
  - Used with **k = {1, 3, 5, 7}** to test different neighborhood sizes.
  - Distance metric: **Euclidean distance**.

- **Validation Strategies:**
  - **Leave-One-Out Cross-Validation (LOO-CV)**
  - **Leave-Replicas-Out Cross-Validation (LRO-CV)**

- **Evaluation Metric:**
  - **C-Index** calculated for each predicted variable (**c_total, Cd, Pb**).

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-Learn

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/junaidraz1/knn-metal-regression.git
