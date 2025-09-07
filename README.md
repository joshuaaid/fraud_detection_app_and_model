# Fraud Detection Project

This repository contains a simple machine learning project for detecting fraudulent financial transactions using the [Fraud Detection Dataset](https://www.kaggle.com/datasets/amanalisiddiqui/fraud-detection-dataset?resource=download).

## Files

- **analysis_model.ipynb**  
  Jupyter notebook for data analysis, feature engineering, and model training.

- **fraud_detection_pipeline.pkl**  
  Saved machine learning pipeline used for predictions.

- **fraud_detection.py**  
  Streamlit web application that loads the trained pipeline and predicts if a transaction is fraudulent based on user inputs.

## Usage

Run the Streamlit app:

```bash
streamlit run fraud_detection.py
