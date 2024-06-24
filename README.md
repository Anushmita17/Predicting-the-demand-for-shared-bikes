# Prediction of bike demand of a bike-sharing system.
> This project aims to predict the demand for shared bikes using machine learning techniques. We analyze various factors such as weather conditions, time of year, and historical usage patterns to develop a robust model that accurately forecasts bike rental counts.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Background of the Project
Bike-sharing systems provide bikes for short-term basis for a price or free, use to the public, typically through a computer-controlled dock system. Users can rent bikes from one dock and return them to another, promoting eco-friendly transportation.
- Business Problem
BoomBikes, a US-based bike-sharing provider, has experienced a significant revenue decline due to the COVID-19 pandemic. The company aims to develop a strategic business plan to boost revenue post-pandemic by understanding the factors that influence bike demand. This will help them prepare to meet future demand and gain a competitive edge in the market.
- Dataset
The dataset used for this project contains daily records of bike rentals, including variables such as temperature, humidity, windspeed, and categorical data like season, month, day of the week, and weather situation. The primary goal is to use these variables to model and predict the total bike rental count ('cnt').

## Conclusions
- Conclusion 1: The linear regression model developed in this project has an R squared value of 0.83, indicating that 83% of the variance in bike rental demand can be explained by the model's variables.
- Conclusion 2 Temperature, apparent temperature, humidity, and windspeed are significant numerical predictors of bike rental demand, suggesting that weather conditions greatly influence the number of bike rentals.
- Conclusion 3  Categorical variables derived from season, day of the week, month, and weather situation also significantly impact bike rental demand, demonstrating that both temporal and weather-related factors are crucial in predicting bike rentals.
- Conclusion 4 The high predictive power of the selected variables allows BoomBikes to strategically adjust their operations and marketing efforts based on expected changes in these factors, potentially increasing their market share and revenue post-pandemic.


## Technologies Used
- Python - Version 3.9
- Pandas - Version 1.3.3: For data manipulation and analysis.
- NumPy - Version 1.21.2: For numerical computing.
- Matplotlib - Version 3.4.3: For data visualization.
- Seaborn - Version 0.11.2: For statistical data visualization.
- Scikit-learn - Version 0.24.2: For machine learning algorithms and model building.


## Acknowledgements
Give credit here.
- This project was inspired by a data analysis and modeling exercise aimed at understanding and predicting bike rental demand.
- References: Data dictionary and dataset provided as part of the project resources.
- This project was based on the guidelines provided by UpGrad.


## Contact
Created by Anushmita Mukherjee [@Anushmita17] - feel free to contact me!
