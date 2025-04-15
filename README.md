# Bike Demand Prediction Using Multiple Linear Regression
> A regression model to understand and predict daily demand for shared bikes based on weather, calendar, and seasonal factors.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project builds a multiple linear regression model to predict the number of bike rentals per day for a U.S.-based shared bike service, BoomBikes.
- The business problem is to identify key factors that influence demand and use them to forecast future rental needs, especially in a post-pandemic scenario.
- The dataset used is `download.csv`, which includes variables like temperature, humidity, season, weekday, weather situation, and actual rental counts.

## Conclusions
- The final model includes 16 statistically significant variables and achieved an R-squared of **0.8573** on the test set.
- Variables such as **year, temperature, working days**, and **weather conditions** have the most impact on demand.
- The model generalizes well and passes residual checks including normality and constant variance assumptions.
- Insights from this model can help BoomBikes improve demand forecasting and operational planning.

## Technologies Used
- Python - 3.11.7
- pandas - 2.1.4
- numpy - 1.26.4
- matplotlib - 3.8.0
- seaborn - 0.12.2
- statsmodels - 0.14.0
- scikit-learn - 1.2.2

## Acknowledgements
- This project was inspired by a regression problem shared as part of a business analytics and machine learning course.
- Dataset and business case were provided as part of the course curriculum.
- The dataset is obtained from the following  

  > Fanaee-T, Hadi, and Gama, Joao, *Event labeling combining ensemble detectors and background knowledge*, Progress in Artificial Intelligence (2013): pp. 1–15, Springer Berlin Heidelberg.  
  > doi: [10.1007/s13748-013-0040-3](http://dx.doi.org/10.1007/s13748-013-0040-3)

## Contact
Created by [@tatha](https://github.com/tatha) - feel free to reach out via GitHub!
