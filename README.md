# Real Estate House Price Prediction

## Overview
This project is a machine learning-based real estate price prediction system focused on Bangalore housing prices. It consists of three main components:
- **Model**: A Jupyter notebook pipeline for data exploration, preprocessing, and training a regression model to predict home prices.
- **Server**: A Flask backend server that loads the trained model and exposes REST API endpoints to serve price predictions and location data.
- **Client**: A simple web-based frontend built with HTML, CSS, and JavaScript that allows users to input property details and get estimated prices in real-time.

## Features
- Predicts home prices based on key features such as total square feet, number of bedrooms (BHK), number of bathrooms, and location.
- Dynamic location dropdown populated from the backend.
- REST API endpoints for fetching location names and predicting prices.
- User-friendly web interface for easy interaction.

## Technologies Used
- **Python**: For backend server and machine learning model development.
- **Flask**: Lightweight web framework to build REST API server.
- **Jupyter Notebook**: For data analysis, feature engineering, and model training pipeline.
- **scikit-learn**: Machine learning library used for regression modeling.
- **JavaScript, HTML, CSS**: For building the client-side user interface.
- **Pickle**: For serializing the trained machine learning model.

## Getting Started
1. Install required Python packages (Flask, scikit-learn, numpy, pandas).
2. Run the Flask server:
   ```
   python server/server.py
   ```
3. Open `client/app.html` in a web browser.
4. Use the web interface to input property details and get price estimates.

