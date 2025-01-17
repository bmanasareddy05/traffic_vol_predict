# PREDICTION THE TRAFFIC VOLUME ON HIGHWAY

## Overview
This project leverages machine learning techniques to predict traffic volume on highways using various weather and temporal features. The dataset includes information such as time of day, day of the week, temperature, rain, snow, and cloud coverage. Multiple regression models are employed, and the best-performing models are identified through cross-validation.

## Table of contents

* Dataset description <br>
* Data Visualization <br>
* Models implemented <br>
* Results and best model <br>
* How to run the project <br>
* Dependencies <br>
* Further improvement <br>
* Conclusion <br>

## Dataset description
The dataset includes the following features:
* hour, day, month, weekday: Time-related features
* temp: Temperature (converted to Kelvin)
* rain_1h, snow_1h: Precipitation indicators
* clouds_all: Cloud coverage percentage
* traffic_volume: Target variable representing traffic volume

## Data visualization
The project includes following visualizations:
* Daytime traffic volume , Nighttime trafiic volume
* Business_day traffic , Weekend traffic
* Average traffic volume vs Temperature and weather

## Models implemented
* Linear Regression: A simple baseline model
* Random Forest Regressor: A robust ensemble method
* Gradient Boosting Regressor: A model focused on reducing errors iteratively

## Results 
