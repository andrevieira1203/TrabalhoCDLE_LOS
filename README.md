# CDLE : ICU Length of Stay Prediction

## Description

This repository contains the work developed for the **CDLE (Data Science in Life and Environment)** course, focusing on **statistical analysis and data visualization of ICU patient data**, as well as **predicting the Length of Stay (LOS)** in the ICU using machine learning techniques and pipelines.

The goal is to extract meaningful insights from clinical data and build predictive models capable of estimating how long a patient will remain in the Intensive Care Unit, which is a key metric for hospital resource management.

---

## Repository Structure

```
TrabalhoCDLE_LOS/
│
├── InitialDatasets/          # Raw datasets used as input
├── TrabalhoFinal/            # Final version of the project
├── TABELASFILTERED.ipynb     # Data filtering and preprocessing
├── TRABALHO.ipynb            # Main analysis notebook
├── TrabalhoCDLE.ipynb        # CDLE course project notebook
├── visualização.ipynb        # Data visualization notebook
├── TABELAFINAL2.csv          # Final processed dataset
└── README.md                 # Project documentation
```

---

## Notebooks Overview

### `TABELASFILTERED.ipynb`
Data cleaning and filtering pipeline — handles missing values, outliers, and prepares the raw datasets for analysis.

### `TRABALHO.ipynb`
Main project notebook covering the full analysis workflow: exploratory data analysis, feature engineering, model training, and evaluation.

### `TrabalhoCDLE.ipynb`
Course-specific notebook with the structured analysis developed for the CDLE assignment.

### `visualização.ipynb`
Dedicated notebook for data visualization — charts and plots used to communicate findings and understand patterns in ICU patient data.

---

## Objectives

- Perform **exploratory data analysis (EDA)** on ICU patient records
- Identify the most relevant clinical features correlated with **length of stay**
- Build and evaluate **machine learning models** to predict LOS
- Compare different ML algorithms and select the best-performing pipeline

---

## Machine Learning Pipeline

The predictive modeling process includes:

- **Data preprocessing** — normalization, encoding, imputation
- **Feature selection** — identifying the most informative clinical variables
- **Model training** — regression/classification models for LOS prediction
- **Evaluation** — metrics such as MAE, RMSE, R², accuracy, and AUC-ROC
- **Pipeline automation** — end-to-end ML pipeline for reproducibility

---

## Technologies & Libraries

- **Python 3**
- **Jupyter Notebook**
- Likely libraries:
  - `pandas`, `numpy` — data manipulation
  - `matplotlib`, `seaborn` — visualization
  - `scikit-learn` — ML models and pipelines
  - `scipy`, `statsmodels` — statistical analysis

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/andrevieira1203/TrabalhoCDLE_LOS.git
   cd TrabalhoCDLE_LOS
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels jupyter
   ```

3. Run the notebooks in the following recommended order:
   ```bash
   # 1. Data filtering and preprocessing
   jupyter notebook TABELASFILTERED.ipynb

   # 2. Main analysis
   jupyter notebook TRABALHO.ipynb

   # 3. Visualizations
   jupyter notebook visualização.ipynb
   ```

---

## Languages

| Language | Percentage |
|---|---|
| Jupyter Notebook | 100% |

---
