# Google Summer of Code 2018 Project Description

## Project Name : ```Automatic Forecasting```

## Organisation : [`Python Software Foundation`](https://www.python.org/psf/) [`GSoC Organisation Link`](https://summerofcode.withgoogle.com/organizations/4812284052897792/)

## Sub-Org : [`Statsmodels`](http://www.statsmodels.org/stable/index.html)

## Project Abstract : 
The aim of the project is to implement an automatic forecasting infrastructure for Statsmodels similar to `auto.arima()`/`ets()` of the `forecast` package in `R`. The goals will be to use the existing models of Statsmodels like SARIMAX and ES to build a forecasting method that would automatically detect the best model and forecast values based on that model. 

`Automatic forecasting` algorithms determine an appropriate time series model, estimate the parameters and compute the forecasts. They are appropriate for various time series patterns, and applicable to large numbers of series without user intervention. The most popular automatic forecasting algorithms are based on either exponential smoothing(ES) or ARIMA models.

## GSoC Project link : https://summerofcode.withgoogle.com/projects/#5366810581401600

##### My project is completely covered by a single Pull Request and all the commits in this Pull request are mine as a part of GSoC.
## Project Development link (Single Pull Request): https://github.com/statsmodels/statsmodels/pull/4621

## Project Blog : https://blogs.python-gsoc.org/abhijeet-panda/

## Project Milestones :
1. Automatic model Selection for SARIMAX models.
2. Automatic model selection for Exponential Smoothing models.
3. Automatic box-cox transformation.(Parameter Prediction)
4. Forecast and ForecastSet classes to hold and compare different time-series models.
5. Time Series Cross Validation module.

## Project Progress over the summer:
The project has met all the requirements that was initially proposed. The project is completely functional and can be used by others for testing purpose only.
The project is in a early stage now and more rigorous testing is coming its way before finally being merged to the Statsmodels repository.

## TODO Projects Components 
1. More rigorous testing by a variety of users and variety of real-time data.
2. Adding a few more functionalitites by taking feeback from the  user community.

All the code written by me from 14th May 2018 to 13th August 2018 for the GSoC 2018 program is also present [here] (automatic.zip)
