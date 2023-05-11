# Weather-Prediction-Using-RNN
This repository contains the code and resources for a weather prediction model developed using Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) architecture. The model is trained on a large dataset of weather data from Kharagpur and is capable of predicting the weather conditions for the next 15 days.


![Screenshot (731)](https://github.com/Pallabpal/Weather-Prediction-Using-RNN/assets/122145541/c8659089-4675-4aee-90bc-fae1bbbb1a68)


# Dataset
Weather data is kept by numerous organisations, including the National Weather Service,
Indian Space Research Organization, Indian Meteorological Department, and National
Aeronautics and Space Administration (NASA). Storing weather data is important for
various reasons other than Weather Forecasting. Weather data is also used to study
long-term climate patterns, including trends in temperature, precipitation, and other me-
teorological variables. This information is used to develop models of how the climate
is changing over time and to understand the impacts of climate change on ecosystems,
human health, and infrastructure. Energy companies also require such data to forecast
demand for energy, such as electricity or natural gas, based on factors like temperature,
humidity, and wind speed. This information is used to manage energy supply and demand
more efficiently, which can help to reduce costs and improve reliability.
The data for this project has been extracted from the NASA Power API. API stands
for Application Programming Interface, which is a set of protocols, routines, and tools for
building software applications. APIs allow different software systems to communicate with each other and share data
in a standardized way, making it easier to integrate different software components into
a cohesive application. Data extracted from this API had 4108 records and 31 features
including the date of observation.
# Model Architecture
The weather prediction model utilizes the LSTM architecture, a type of RNN that is well-suited for sequence prediction tasks. The LSTM cells in the model help capture long-term dependencies in the weather data, allowing for accurate predictions. The model is implemented using the TensorFlow framework, a popular choice for deep learning projects.
The follwing link provides a detail Architecture of LSTM model:
https://colah.github.io/posts/2015-08-Understanding-LSTMs/
# Prediction
Once the model is trained, it can be used to make weather predictions for future dates. Given the current weather conditions as input, the model generates predictions for the next 15 days. The predicted weather data includes temperature, humidity, wind speed, and precipitation for each day.
# Usage
To use this weather prediction model, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies specified in the requirements.txt file.
3. Prepare your own dataset or use the provided dataset of weather data from Kharagpur.
4. Train the model using the prepared dataset by running the training script.
5. Once the model is trained, you can use it to make weather predictions by providing the current weather conditions as input.
# Contributing
Contributions to this weather prediction model are welcome. If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request. Your contributions can help enhance the accuracy and performance of the model.
