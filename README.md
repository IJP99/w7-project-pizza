# Perfectly Distributed Pizza: Machine Learning

[Summary](#Summary)
[Observations](#Observations)
[Conclusions](#Conclusions)
[Slides](#Slides)
[Install](#Install)
[Development](#Development)
[Contributors](#Contributors)


## Summary
This project uses pizza delivery data (for the fictional restaurant Perfectly Distributed Pizza) from Kaggle over the course of 2015. The data was cleaned and separated into time and categorical data before being used to train a range of machine learning models including Meta's Prophet, decision trees, random forests and KNN. 

The analyses and models showed limited predictive ability due to the limited time window, though actionable conclusions were drawn from aspects of seasonality and size. The analysis was developed and presented as part of Ironhack's Data Analytics bootcamp. 



## Observations
* Time series data showed promising results in daily seasonality. Prophet models were able to predict daily totals with a satisfactorily low level of error at 30-,60- and 90-day intervals.
* Due to the limited date range, time series data was unable to produce useful forecasts for monthly/yearly seasonality. 
* Regarding the analysis of the categorical columns (Pizza name, size and type), the less contributive conclusion in terms of predictions was the "Pizza name" due to the lack of correlation with other variables and the unstable demand that makes almost unpredictable in the machine learning model.
* On the other hand, Size and Type got good result in the predictions mostly in the case of the size to its close relation to the price.

## Conclusions
* Perfectly Distributed Pizza could use the daily seasonality trends to create an optimised staffing rota with a reasonable degree of confidence. This would hopefully elicit benefits in maximum output for peak ordering times.
* Underperformance in June and October order volumes suggest indicative time windows for promotional activity.
* Perfectly Distributed Pizza should consider ways to drive up customer order volumes in 2016 if volumes continue dropping, in line with forecasts. 
* While the demand in the pizzas could be a bit unpredictable the pizza dough could be manage with no problems in term of demand as well as this may help in the improvement of inventory


## Slides

The slides presenting the data and analysis can be found at: [slides]: ['https://docs.google.com/presentation/d/1ub4H2H7tk_0YpSEVtHp80DNCZmr6satXiwxbeQ7tzh0/edit?usp=sharing']

## Install

### Python

The data cleaning and machine learning in Python used the following packages:
* numpy
* pandas
* matplotlib
* seaborn
* scikit.learn
* Prophet

The versions for the above packages can be found in the requirements text file.

## Development

Data was provided by Ironhack and was analysed, transformed and plotted in Jupyter Lab and Tableau.

## Contributors

mhga94
IJP99
Pantoh
RajashreeHajare