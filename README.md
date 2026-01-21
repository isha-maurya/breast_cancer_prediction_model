Breast Cancer Prediction Model
A machine learning web application that predicts whether a breast tumor is Malignant (Cancerous) or Benign (Non-Cancerous) based on medical feature inputs.

Project Overview
This project implements a Logistic Regression model trained on the Breast Cancer Wisconsin (Diagnostic) Dataset. It uses a Flask backend to serve the model and a Bootstrap-based frontend to accept user input and display diagnostic results.

Key Features
Prediction Engine: Uses Logistic Regression with StandardScaler for data normalization (Accuracy: ~97%).
Interactive Interface: Web dashboard for entering tumor features (Radius, Texture, Perimeter, etc.).
Visual Feedback: Displays dynamic result cards (Cancerous/Not Cancerous) with corresponding visual indicators.

Tech Stack
Backend: Python, Flask
ML Libraries: Scikit-learn, Pandas, NumPy
Frontend: HTML5, CSS3, Bootstrap
Deployment: Localhost (Development)

How to Run
Clone the repository

Bash
git clone [INSERT YOUR REPO LINK HERE]
cd [YOUR REPO NAME]
Install dependencies

Bash
pip install flask pandas scikit-learn numpy
Run the application

Bash
python app.py
Access the App Open your browser and navigate to: http://127.0.0.1:5000/

Model Details
Dataset: Breast Cancer Wisconsin (Diagnostic) Data Set
Preprocessing: Data is scaled using StandardScaler to ensure all features contribute equally to the result.
]
Algorithm: Logistic Regression (Binary Classification).
