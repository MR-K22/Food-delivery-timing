

# Food Delivery Time Prediction

This project predicts the time taken for food delivery based on various features such as delivery partner age, ratings, and the calculated distance between the restaurant and delivery location. The prediction model is built using an LSTM neural network.

## Project Overview

The goal of this project is to accurately forecast food delivery times using machine learning. The dataset contains delivery partner details, restaurant and delivery locations, and delivery time records. The distance between the restaurant and delivery spot is calculated using the Haversine formula based on latitude and longitude.

## Features Used

- Age of the delivery partner
- Ratings of the delivery partner
- Distance between restaurant and delivery location (calculated using latitude and longitude)

## Data Exploration

- Distance positively correlates with delivery time.
- Younger delivery partners tend to deliver faster.
- Higher rated delivery partners complete deliveries quicker.
- Vehicle type and order type have minimal impact on delivery time.

## Model

A Long Short-Term Memory (LSTM) neural network is trained on the delivery data to predict delivery times, using the three features above.

## Installation

1. Clone the repository.
2. Install required Python libraries:
   ```bash
   pip install pandas numpy tensorflow keras scikit-learn plotly
   ```
3. Prepare the dataset file `contentdeliverytime.txt` in the working directory as expected by the script.

## Usage

Run the script to train the model and make predictions:

```bash
python food_delivery_time_prediction.py
```

Follow the prompts to input delivery partner age, ratings, and distance to get the predicted delivery time in minutes.

## Files

- `food_delivery_time_prediction.py`: Main script for data processing, model training, and prediction.


[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/68022021/f4ace000-1e23-43f0-8fd9-88f936f417b5/food_delivery_time_prediction.py)
