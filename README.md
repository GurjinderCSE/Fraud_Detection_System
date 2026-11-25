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
## Dataset Information
The project uses AIML Dataset.csv for transaction data analysis.
Dataset Size: Approximately 470 MB.
The dataset is not included in this GitHub repository because it exceeds the browser upload limit.
Users need to keep the dataset in the project folder to run the dataset analysis code.
