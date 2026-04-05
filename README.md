Forest Fire Prediction System

This project predicts the **Fire Weather Index (FWI)** using Machine Learning.
It uses a trained Ridge Regression model and a Flask web application to take user input and generate predictions.

##  Features
- Predicts Fire Weather Index (FWI)
- User-friendly web interface using Flask
- Real-time prediction
- Data preprocessing using StandardScaler

##  Tech Stack
- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
ML Project1/
│
├── application.py        # Flask app
├── models/
│   ├── ridge.pkl         # Trained model
│   └── scaler.pkl        # Scaler
├── templates/
│   ├── index.html        # Input form
│   └── home.html         # Output page
├── notebook/             # Jupyter notebooks
├── requirements.txt      # Dependencies
└── README.md
