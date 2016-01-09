---
title: "CityBikes – Forecasting bikes/docks availability of a bike-sharing system in San Francisco Bay Area"
layout: post
#photo_url: "/res/bikeShare.jpg"
description: ""
categories: jekyll update blogg github
---

![http://www.bayareabikeshare.com/](/res/bikeShare.jpg)
During the last 3 months, I got the chance to join a team of data scientists as intern here in Oslo @ [IntelCom](http://intelcom.no). To learn more about the everyday tools and tasks of a Data Scientist, I got to build a predictive app based on data from [BikeShare](http://www.bayareabikeshare.com). The data is public and available [here](http://www.bayareabikeshare.com/open-data).

The idea behind this project is to help the people working on the maintenance of any similar shared cityBikes system. They already have realtime data informing them about the status of the stations:
* the number of bikes available,
* the number of docks available,
* which bike just arrived/left from/for a trip.

Nevertheless by forecasting the flow of bikes at every station in realtime, we can predict (within a certain confidence interval) which stations will require "maintenance" 1-hour or 2-hours ahead of the shortage. 
This allows to automate the planification of the maintenance by providing an optimized travel path to refurnish/remove bikes.

The plot below is just some preliminary result showing the demand of shared bikes in San Francisco Bay Area. We can see roughly that both predictions are not too bad at predicting the variations but both tend to overestimate still the flow of bikes leaving the stations. I will soon share more details on the exploratory analysis and the resulting dashboard.

<a href="https://plot.ly/~PatrickMerlot/1671/citybikesprediction-of-bike-demand-from-san-francisco-caltrain-townsend-at-4th/" target="_blank">
   <img src="/res/cityBikes_Prediction_preliminaryResult.png" alt="Preliminary result forecasting the flow of shared bikes in San Francisco" width="2048">
</a>