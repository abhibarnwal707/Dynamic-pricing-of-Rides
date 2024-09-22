# Ride Pricing Prediction App

This Streamlit application implements a machine learning-based pricing model for ride-sharing services. Users can interact with the app to estimate ride prices based on different input parameters, leveraging a trained Random Forest Regressor. The app also offers insights through various data visualizations comparing model predictions with actual ride prices.

## Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Setup](#setup)
- [Running the Application](#running-the-application)

## Overview

The Ride Pricing Prediction App is designed with Streamlit to provide an easy-to-use web interface for users to predict ride costs. The app is backed by a Random Forest Regressor model, trained on historical data from ride-sharing services. It allows users to explore pricing by adjusting various input parameters.

## Key Features

- **Price Estimation**: Enter key ride attributes like the number of passengers, available drivers, vehicle type, and ride duration to predict the ride price.
- **Data Visualization**: Interactive graphs (using Plotly) compare the model's predictions with actual historical ride data.
- **Profitability Insights**: Analyze ride profitability with charts showing distributions of high and low-profit rides.
- **Data Handling**: Automatically processes missing or incomplete input data for smoother predictions.
- **Machine Learning**: Utilizes a Random Forest Regressor for accurate and robust price predictions.

## Setup

1. Clone the repository to your local machine:

```bash
git clone https://github.com/abhibarnwal707/Dynamic-pricing-of-Rides.git
```

2. Navigate to the project directory:

```bash
cd dynamic-pricing-app
```

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage
Place your data files (dynamic_pricing.csv, test_data.csv) in the project directory.

Run the Streamlit app:

```bash
streamlit run app.py

```

The app will open in your default web browser. Use the sliders and input fields to adjust the parameters and get the predicted ride price.
Screenshots
Include any relevant screenshots or GIFs of your app in action here.

License
This project is licensed under the MIT License.

