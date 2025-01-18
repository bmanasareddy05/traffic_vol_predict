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

## Results and Best model
The project evaluates models using 5-fold cross-validation. The results are stored in __fold_accuracies.csv__.The best model is saved using the pickle library for easy reproducibility.
__Best Model__:Gradient Boosting Regressor with an R² score of 0.89.

## How to run the project
Open `traffic_volume.ipynb` then click on open in colab.Then run it.

## Dependencies
* numpy
* pandas
* scikit-learn
* matplotlib

## Further improvement
* Incorporate additional features such as traffic accidents or events.
* Optimize hyperparameters using grid search.
* Experiment with neural networks for improved accuracy.

## Conclusion
### Conclusion

This project successfully demonstrates the prediction of traffic volume using machine learning models like Linear Regression, Random Forest, and Gradient Boosting. By evaluating these models through 5-fold cross-validation, we identified the best-performing model based on R² scores. The project provides a clear workflow, from data preprocessing to model evaluation, ensuring reproducibility. The use of libraries like `scikit-learn` and `pandas` emphasizes the efficiency and scalability of the approach. The included dataset, and code ensure that users can easily replicate and build upon this work.
