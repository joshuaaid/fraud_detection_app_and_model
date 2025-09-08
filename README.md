# Fraud Detection Project

This project demonstrates a machine learning workflow for detecting fraudulent financial transactions.  
It uses the [Fraud Detection Dataset] to build a predictive model and provides a simple Streamlit app for testing predictions interactively.

## Files

- **analysis_model.ipynb**  
  Notebook containing exploratory data analysis (EDA), feature engineering, model training, and evaluation.

- **fraud_detection_pipeline.pkl**  
  The trained machine learning pipeline exported with `joblib`.  
  It includes preprocessing steps and the final classification model.

- **fraud_detection.py**  
  Streamlit web application. Loads the trained pipeline and allows users to input transaction details (type, amount, balances) to get a fraud prediction.

## How to Run

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn joblib streamlit
2. Start the Streamlit app:
   ```bash
    streamlit run fraud_detection.py
3.Enter transaction details in the interface.

  The app will display whether the transaction is likely fraudulent (1) or legitimate (0).
