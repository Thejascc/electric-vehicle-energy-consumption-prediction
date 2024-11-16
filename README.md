# Electric Vehicle Energy Consumption Prediction

## Project Overview

This project aims to predict the energy consumption of electric vehicle (EV) trips based on various factors such as trip distance, time of day, current, maximum cell temperature of the battery, and trip time length. By developing a machine learning model, the goal is to estimate the energy consumed during an EV trip, allowing for more efficient energy management, battery usage, and route planning.

## Objective

The primary objective of this project is to use machine learning techniques, particularly the Gradient Boosting Regressor, to predict energy consumption. Accurate predictions can help in:
- Optimizing energy usage during trips
- Enhancing vehicle performance
- Managing battery life
- Providing insights for EV users for better charging and route planning

## Dataset

The dataset contains information related to trips taken by electric vehicles, including:
- Trip Distance
- Time of Day
- Current
- Maximum Cell Temperature of Battery
- Trip Time Length
- Trip Energy Consumption (log-transformed)

These features are used to predict the energy consumption during each trip.

## Model Used

The model used in this project is the **Gradient Boosting Regressor**, a powerful machine learning technique for regression tasks. This model was trained using a set of features from the dataset to predict energy consumption.

## How It Works

1. **Data Preprocessing**: The dataset was cleaned and normalized to remove any inconsistencies.
2. **Feature Selection**: The most relevant features were selected to train the model.
3. **Model Training**: The Gradient Boosting Regressor model was trained using the selected features and target variable.
4. **Prediction**: The trained model can now predict energy consumption based on new trip data entered by the user.

## Usage

You can use the `get_prediction()` function to input the details of an EV trip and get an estimated energy consumption value.

To run the code, make sure to:
1. Clone this repository.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the script to input trip details and get predictions.

```bash
git clone https://github.com/<your-github-username>/electric-vehicle-energy-consumption-prediction.git
cd electric-vehicle-energy-consumption-prediction
pip install -r requirements.txt
python predict.py
