# Mental Fitness Tracker
A Flask-based AI-powered mental health analysis system built during my AI Developer Internship at Edunet Foundation. The application collects user inputs and predicts their mental fitness score using a trained machine learning model.

# Objective
To support self-awareness and mental well-being by providing insights into stress levels, emotional balance, and daily mood patterns.

# Features
Web-based interface using Flask and HTML
Predicts mental wellness score using a machine learning regression model
Accepts user lifestyle and emotional inputs
Displays clear prediction results
Easily extendable for new datasets or parameters

# Technologies Used
Python
Flask
Scikit-learn
Pandas
NumPy
HTML, CSS

# Project Structure
app.py                   # Main Flask app
model.sav                # Trained machine learning model
templates/
    index.html           # Input form page
    result.html          # Output display page
    about.html           # App information page
static/                  # CSS and other static files (if used)
requirements.txt         # Project dependencies

# Installation and Run Instructions

# Install required dependencies:

pip install -r requirements.txt

# Run the application:

python app.py


# Open in a browser:

http://127.0.0.1:5000/

# How the Prediction Works

User enters responses in the input form.
Inputs are processed and encoded.
The trained machine learning model predicts the mental fitness score.
The result is displayed on the results page.

# Internship Context

This project was developed as part of the AI Developer Internship at Edunet Foundation (AICTE Program). The development involved dataset preprocessing, model training and evaluation, front-end interface creation, and application deployment.
