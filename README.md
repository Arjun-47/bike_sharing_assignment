# Boom Bike Sharing Assignment
> Multi-Linear Regression analysis on Bike Sharing dataset to build a stable model to determine change in total rental bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Linear regression analysis performed on Boom bikes sharing dataset to build a model to determine the change in total rental bikes
- BoomBikes is a bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario
- It has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. So, we are performing Linear Regression analysis on the Boombikes data to build a model to determine the change in total rental bikes
- We are using dataset from boombikes for 2018 & 2019 for analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The final Linear Regression model is able to explain `74%` of change in total rental bikes
- Below are the features used to build the model
    - Year
    - Sep [September]
    - Sat [Saturday]
    - workingday
    - Light Snow
    - Spring
    - windspeed
    - Jan
    - Mist + Cloudy
    - Winter
    - Summer
- R-square value of the model is `78` and R-sqaure value between y_test & y_pred is `74`

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python - 3.8.5
- numpy - 1.19.2
- pandas - 1.1.3
- matplotlib - 3.3.2
- seaborn - 0.11.0
- sklearn - 0.23.2
- statsmodels - 0.12.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- References for validation of linear assumptions are taken from [Step-by-step-assumptions-linear-regression](https://www.kaggle.com/shrutimechlearn/step-by-step-assumptions-linear-regression)
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@Arjun-47](https://github.com/Arjun-47) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->