# Flight Price Prediction Web App

This project is a **Flight Price Prediction** web application developed using **Flask**, **Python**, and **Machine Learning**. The app predicts the price of a flight ticket based on various factors such as the departure date, airline, stops, and more. The machine learning model used for prediction is a Random Forest Regressor.

## Project Overview

This web application predicts flight ticket prices based on the following user inputs:
- **Departure Time**
- **Arrival Time**
- **Total Stops**
- **Airline**
- **Source and Destination Cities**

The model uses historical flight data to predict the price based on the features provided by the user.

## Features

- **User-friendly Interface**: A simple, clean UI to input flight details.
- **Flight Price Prediction**: Predicts flight prices using a machine learning model.
- **Multiple Airlines and Sources**: Supports various airlines and source/destination combinations.
- **Real-time Prediction**: Shows predicted prices in real-time based on user inputs.

## Tech Stack

- **Flask**: Web framework to create the web app.
- **scikit-learn**: For machine learning model (Random Forest Regressor).
- **Pandas**: For handling data and pre-processing.
- **HTML/CSS**: For the frontend.

## Files in this Project

- `app.py`: The main Python file that contains the Flask app logic.
- `flight_rf.pkl`: The pre-trained machine learning model (Random Forest Regressor).
- `flight.html`: The HTML file for the frontend.
- `README.md`: Documentation for the project.

## How to Run the Application Locally

### Step 1: Clone the Repository

First, clone the repository to your local machine.

```bash
git clone https://github.com/your-username/flight-price-prediction.git
cd flight-price-prediction
