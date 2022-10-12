# Boom Bikes
> Its a bike sharing project, facing difficult due to covid, so we need to analize data, and find out the factors which effect sales in future. And make Boom Bikes profitable again.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- days.csv, containing 16 features & 730 records

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In Numerical variable temp & atemp is positivily correlated with target variable, where as humidity & windspeed is negativily correlated.
- Categorical features like weekdays, days & working days have no major effect on target variable, but year, weathersit, month, season have major effect on target variable.
- High collinearity between temp & atemp
- Feature like Year, Light Snow & Spring are major predictor.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- datetime
- calendar
- statsmodels
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on Machine learning on Linear Regression.


## Contact
Created by [@arvindkjangid] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->