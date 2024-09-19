# Bike Sharing
> Bike Sharing Case Study Analysis <br>
Author : G Raghu Vamshi <br>
Date : 19-09-2024

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Overview:

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.

> Aims to find the significant in predicting the demand for shared bikes.

> Analyzes the variables which describe the bike demands

- Business Problem:
A bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
***The company wants to know:***
	- Which variables are significant in predicting the demand for shared bikes.
	- How well those variables describe the bike demands
- Data Source: 'day.csv' dataset is used here.

## Conclusions
Based on the observations following are high impacts:

- Based on the R2 Square value (0.804) on the test model evaluation predicts that this model is good.
- Coefficients:
	- Positive Coefficients: yr, temp, season_summer, season_winter, mnth_Sep, weekday_Saturday
	- Negative Coefficients: hum, windspeed, mnth_July, weekday_Sunday, weathersit_Light Snow, weathersit_Mist and Cloud
- On year 2019, the bike rental has increased.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupiter Notebook: 6.5.4
- Python: 3.11.3
- Numpy: 1.24.3
- Pandas: 1.5.3
- Seaborn: 0.12.2
- Matplotlib: 3.7.1
- Sklearn: 1.2.2
- statsmodels: 0.13.5

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [[@Vamshi-1999](https://github.com/Vamshi-1999)] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
