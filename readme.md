# **Heart Disease Prediction App**

## Overview
This project is a Streamlit-based web application for predicting heart disease severity using a pre-trained machine learning model. The model takes various patient health metrics as input and provides a prediction on the likelihood of heart disease.

## Features
- User-friendly web interface built with Streamlit
- Accepts patient details such as age, cholesterol level, heart rate, and more
- Uses a pre-trained machine learning model to predict heart disease severity
- Displays prediction results in an easy-to-understand format

## Files in This Repository
- `app.py` - Main Streamlit application script
- `heart_disease_pred_model.pkl` - Pre-trained machine learning model
- `heart_disease_data.csv` - Dataset used for training the model
- `Heart_Disease_Prediction.ipynb` - Jupyter notebook containing data preprocessing, model training, and evaluation

## Installation
To run the application locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/hamzakamelen/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the app in your browser after running `streamlit run app.py`
2. Enter the patient's health details in the provided fields
3. Click the "Predict Heart Disease Severity" button
4. View the model's prediction for heart disease severity

## Contributing
Feel free to contribute to this project by submitting issues or pull requests.

## License
This project is licensed under the MIT License.

---
Developed by Hamza Kamelen