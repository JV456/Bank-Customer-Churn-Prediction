# Bank Customer Churn Prediction

This project involves developing an end-to-end deep learning project (ANN) for predicting bank customer churn using a tabular dataset. The project utilizes TensorFlow and Keras to build an Artificial Neural Network (ANN) for binary classification. Additionally, the trained model is deployed via a web application using Streamlit.

## Project Workflow

### 1. Dataset
The dataset used is `churn_modelling.csv`, which includes the following features:
- **Independent Features**: `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- **Target Feature**: `Exited` (indicating whether a customer has left the bank or not)

### 2. Data Preprocessing
- Performed **basic feature engineering**:
  - Converted categorical variables into numerical format.
  - Applied standardization or normalization to the numerical features.

### 3. ANN Model Training
- Built an **Artificial Neural Network (ANN)** with TensorFlow and Keras:
  - Input layer with features from the dataset.
  - Multiple hidden layers with configurable nodes and activation functions.
  - Dropout layers to prevent overfitting.
  - Output layer for binary classification (activated using sigmoid).
- Trained the ANN using:
  - Forward propagation.
  - Loss function (binary cross-entropy).
  - Optimizers (e.g., Adam).

### 4. Model Saving
- Saved the trained model in a reusable format:
  - `.pickle` file.
  - `.h5` format (for TensorFlow models).

### 5. Deployment
- **Web Application Development**:
  - Built a user-friendly interface using **Streamlit**.
  - Integrated the trained model into the app for real-time predictions.
- **Cloud Deployment**:
  - Deployed the Streamlit web app to **Streamlit Cloud** for access from anywhere.
 
![SimpleANN (2)](https://github.com/user-attachments/assets/d4ccda4b-1f99-434e-8bce-004e55d4bc30)

## Features of the Web App
- Upload customer data for prediction.
- View whether a customer is likely to leave the bank or stay.
- Deployment on Streamlit Cloud for seamless access.

## Acknowledgments
This project is inspired by the need to help banks predict customer churn effectively, enabling better customer retention strategies.
