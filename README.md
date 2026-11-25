# Fraud Detection System:
## Project Overview
This project is a Fraud Detection application developed using Python, Machine Learning and Streamlit.

It takes transaction details from the user and predicts whether a transaction is fraudulent or legitimate using a saved machine learning pipeline.

## Technologies Used
- Python
- Pandas
- Streamlit
- Joblib
- Machine Learning

## Input Features
- Transaction Type
- Transaction Amount
- Old Balance (Sender)
- New Balance (Sender)
- Old Balance (Receiver)
- New Balance (Receiver)

## How to Run

1. Install the required libraries.
2. Keep the Python file and trained model in the same project folder.
3. Open the terminal in the project folder.
4. Run:

streamlit run fraud_detection.py

## Project Output
The application displays a prediction indicating whether the entered transaction is classified as fraudulent or legitimate.

## Note
This is an educational project and its predictions should not be used as the sole basis for real financial decisions.