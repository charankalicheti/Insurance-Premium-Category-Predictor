# Insurance-Premium-Category-Predictor
FastAPI-based ML project for predicting insurance premium categories using user inputs like age, BMI, income, and lifestyle. Includes Pydantic validation, computed features, and a trained model for real-time predictions. Designed for scalable API deployment.
A full-stack Machine Learning application that predicts insurance premium categories using user data such as age, BMI, income, and lifestyle. The project includes a FastAPI backend for predictions and a Streamlit frontend for interactive user input.

Features
🔹 End-to-end ML project (training → deployment)
🔹 FastAPI for high-performance REST APIs
🔹 Streamlit UI for user interaction
🔹 Pydantic validation with computed fields
🔹 Real-time predictions using trained ML model
🔹 Clean and scalable architecture

Tech Stack
   Python
   FastAPI
   Streamlit
   Pandas
   Scikit-learn (Model Training)
   Pickle (Model Serialization)

Project structure
   
├── ml.py              # FastAPI backend
├── app.py             # Streamlit frontend
├── model.pkl          # Trained ML model
├── requirements.txt
└── README.md

ML Features Engineered
   BMI calculation
   Lifestyle risk (based on smoking & BMI)
   Age group classification
   City tier categorization
