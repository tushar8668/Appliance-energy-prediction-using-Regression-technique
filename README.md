<h1 align="center"> Appliance-energy-prediction-using-Regression-technique </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

<p align="center"> 
<img src="https://github.com/AnshRockstar/NYC-Taxi-Trip-Duration-Prediction/blob/main/Images/NYC%20Taxi.jpg" alt="NYC Taxi.jpg"  height="320px">
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
