---
title: "CityBikes – Forecasting bikes/docks availability of a bike-sharing system in San Francisco Bay Area"
layout: post
description: ""
categories: jekyll update blogg github
---


During the last 3 months, I got the chance to join a team of data scientists as intern here in Oslo @ [IntelCom](intelcom.no). To learn more about the everyday tools and tasks of a Data Scientist, I got to build a predictive app based on data from [BikeShare](http://www.bayareabikeshare.com). The data is public and available [here](http://www.bayareabikeshare.com/open-data).

The idea behind this project is to help the people working on the maintenance of any similar shared cityBikes system. By forecasting the flow of bikes at every station in realtime, we can predict which station will require "maintenance" first 1-hour or 2-hours ahead provided with a certain confidence interval, and soon offer an optimized travel path for the maintenance team to refurnish/remove bikes.

The plot below is just some preliminary result showing the demand of shared bikes in San Francisco Bay Area. We can see roughly that both predictions are not too bad at predicting the variations but both tend to overestimate still the flow of bikes leaving the stations. I will soon share more details on the exploratory analysis and the complete webapp I am finishing to build. 

![Preliminary result forecasting the flow of shared bikes in San Francisco](/res/cityBikes_Prediction_preliminaryResult.png)