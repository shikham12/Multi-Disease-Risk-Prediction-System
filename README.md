# Multi-Disease Risk Prediction System

This project implements a machine learning pipeline to predict the risk of **Diabetes, Heart Disease, and Kidney Disease** using patient medical data. It is designed to be flexible, interpretable, and robust to missing data.

## Features

- Separate Random Forest classifiers trained for each disease.
- Handles missing input features with mean-value imputation using training data statistics.
- Predicts continuous risk probabilities, not just binary outcomes.
- Aggregates individual disease risks into an overall risk score.
- Visualizes disease risk with intuitive, color-coded bar charts.
- Supports partial patient data input, enabling predictions even if some disease features are missing.
- Implemented fully in Jupyter Notebook for transparency and ease of use.

## Getting Started

### Prerequisites

- Python 3.7+
- Packages: pandas, numpy, scikit-learn, matplotlib, seaborn

Install required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
