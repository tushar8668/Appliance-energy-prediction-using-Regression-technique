<h1 align="center"> Appliance-energy-prediction-using-Regression-technique </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

<p align="center"> 
<img src="https://github.com/tushar8668/Appliance-energy-prediction-using-Regression-technique/blob/main/Appliance%20Energy%20consumption.jpg" alt="AEP.jpg"  height="320px">
</p>


## Introduction
The purpose of this research is to forecast the electricity consumption of a particular household in Belgium based on the temperature and humidity levels of various rooms in the facility and surrounding weather information over 4.5 months. The data set runs 4.5 months at 10 minutes. A ZigBee wireless sensor network is being used to monitor the home’s temperature and humidity levels. Around 3.3 minutes, each wireless node sent the temperature and humidity data. The wireless data was then averaged across intervals of 10 minutes. Every 10 minutes, m-bus energy meters collected the energy data. The experimental data sets were combined with the weather data from the closest airport weather station (Chievres Airport, Belgium), which was extracted from a public data set from Reliable Prognosis (rp5.ru). The data set has two random variables to test the regression models and exclude non-predictive characteristics (parameters).

## Business Problem Statement
The increasing trend in energy consumption is becoming cause of concern for the entire world, as the energy consumption is increasing year after year so is the carbon and greenhouse gas emission, the majority portion of the electricity generated is consumed by industrial sector but a considerable amount is also consumed by residential sector.
It is important to study the energy consuming behaviour in the residential sector and predict the energy consumption by home appliances as it consume maximum amount of energy in the residence. This project focuses on predicting the energy consumption of home appliances based on humidity and temperature.
This project aims to predict the energy consumption of home appliances. With the advent of smart homes and the rising need for energy management, existing smart home systems can benefit from accurate prediction. If the energy usage can be predicted for every possible state of appliances, then device control can be optimized for energy savings as well. This is a case of Regression analysis which is part of the Supervised Learning problem. Appliance energy usage is the target variable while sensor data and weather data are the feature.

### Project Dataset Summary
* date time year - month-day hour:minute:second
* Appliances - energy use in Wh
* lights - energy use of light fixtures in the house in Wh
* T1 - Temperature in kitchen area, in Celsius
* RH_1 - Humidity in kitchen area, in %
* T2 - Temperature in living room area, in Celsius
* RH_2 - Humidity in living room area, in %
* T3 - Temperature in laundry room area
* RH_3 - Humidity in laundry room area, in %
* T4 - Temperature in office room, in Celsius
* RH_4 - Humidity in office room, in %
* T5 - Temperature in bathroom, in Celsius
* RH_5 - Humidity in bathroom, in %
* T6 - Temperature outside the building (north side), in Celsius
* RH_6 - Humidity outside the building (north side), in %
* T7 - Temperature in ironing room , in Celsius
* RH_7 - Humidity in ironing room, in %
* T8 - Temperature in teenager room 2, in Celsius
* RH_8 - Humidity in teenager room 2, in %
* T9 - Temperature in parents room, in Celsius
* RH_9 - Humidity in parents room, in %
* To - Temperature outside (from Chievres weather station), in Celsius
* Pressure - (from Chievres weather station), in mm Hg
* RH_out Humidity outside (from Chievres weather station) in %
* Wind speed - (from Chievres weather station) - in m/s
* Visibility - (from Chievres weather station), in km
* Tdewpoint - (from Chievres weather station), Â°C
* rv1 - Random variable 1, nondimensional
* rv2 - Random variable 2, nondimensional
  
## Machine learning models used To complete project
* Linear Regression
* Lasso and Ridge Regression
* XGboost Regression
* Gradient Boosting Regression
* Random Forest Regression


## Which model you choose and why ?
I chose a random forest model because it is a powerful and versatile machine learning algorithm that is well-suited for a variety of tasks, including classification and regression. Random forests are also relatively easy to interpret and robust to noise and outliers in the data.<br>

In my project, the random forest model achieved an highest accuracy of 65% and an MSE of 35%. These are both good results, but there is always room for improvement. I plan to perform some feature engineering to see if I can create new features that are more informative for the machine learning algorithm.

## Conclusion 
In this project, we tested a variety of machine learning algorithms for predicting appliance energy consumption. I used a different features, including sensor data, weather data, and appliance state data, to train the model. I found that random forest regression models achieved the highest accuracy.<br>

We can use this model to predict the energy consumption of appliances in a variety of ways.
For example, we can use it to:

* Identify energy - efficient appliances and settings.
* Develop smart home energy management systems that can optimize appliance usage to reduce energy costs.
* Detect anomalous energy consumption patterns that may indicate a problem with an appliance or the electrical system.

For example, we could use the model to predict the energy consumption of a refrigerator over the next 24 hours. This information could be used to develop a smart home energy management system that would automatically turn off the refrigerator if there is no one home and the temperature inside the refrigerator is above a certain threshold.<br>

We could also use the model to identify appliances that are consuming more energy than expected. This information could be used to troubleshoot problems with appliances or to identify areas where energy consumption can be reduced.<br>

Overall, this project demonstrates the feasibility of using random forest models to predict appliance energy consumption. The model we developed achieved a good performance on the test set, and it can be used in a variety of ways to reduce energy consumption and save money.

## Benefits of Appliance Energy Consumption Prediction
An appliance energy prediction project can be helpful for society in a number of ways, including:<br>
* Reducing energy consumption : By predicting appliance energy consumption,consumers can make informed decisions about how to use their appliances in a more energy-efficient way. For example, if a consumer knows that their washing machine is going to use a lot of energy at a certain time, they can choose to run it at a different time or on a different day.
* Saving money on energy bills : By using their appliances more efficiently, consumers can save money on their energy bills. This is especially important for low-income households, which often spend a disproportionate amount of their income on energy costs.
* Improving grid stability : By predicting appliance energy consumption, utilities can better manage the grid and prevent outages. This is important because outages can be disruptive and costly for businesses and consumers.

Overall, appliance energy prediction projects have the potential to make a significant positive impact on society. By reducing energy consumption, and energy bills, appliance energy prediction projects can help to create a more sustainable and equitable future.
