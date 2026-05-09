# Bank_Customer_Churn_Prediction_using_ANN
Built an end-to-end binary classification model using an Artificial Neural Network (ANN) to predict customer churn in a banking dataset. The project includes data preprocessing, feature engineering, model training, and deployment using Streamlit.
***
## Architectural Diagram
![Architecture Design](https://github.com/srirangam-saitej/Bank_Customer_Churn_Prediction_using_ANN/blob/7e78c6bb185d312e70ba5b428d2f92b1a037c860/flow_diagram.png)
***
## Project Overview
This project predicts whether a bank customer is likely to stay with the bank or leave (customer churn prediction) using an Artificial Neural Network (ANN).
The solution covers the complete machine learning workflow from data preprocessing and feature engineering to model deployment using Streamlit.
***
## Problem Statement
Banks often face customer churn, which directly impacts business growth and revenue.
The goal of this project is to build a binary classification model that predicts whether a customer will continue with the bank based on customer and account-related information.
***
## Project Flow
Load and analyze the churn modeling dataset
Perform feature engineering and preprocessing
Handle categorical variables
Apply data standardization
Train an ANN-based deep learning model
Evaluate model performance on test data
Save the trained model in serialized format (.h5, pickle)
Integrate the model with a Streamlit application
Deploy the application on Streamlit Cloud
***
## Tech Stack
* Python
* Pandas & NumPy
* Scikit-learn
* TensorFlow / Keras
* Streamlit
***
## Final Outcome
The final application allows users to provide customer details through a Streamlit interface and predicts whether the customer is likely to churn or continue with the bank. The project demonstrates an end-to-end deep learning implementation including preprocessing, model training, serialization, and deployment.
