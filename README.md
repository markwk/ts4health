# A Self Across Time: Time Series Data Analysis with Python

Slides and sample code for Time Series Data Analysis, Visualization, Modeling and Forecasting with Python for Health and Self

Talk provides code for time series analysis modeling in general and then applies it to quantified self and fitness tracking data from Fitbit, Apple Watch or Oura. 

**Contents**

- [Description](#description)
- [Slides](#slides)
- [Code](#code)
- [Data](#data)
- [References](#references)
  - [Published References](#published-references)
  - [Internet Resources](#internet-resources)
- [About Speaker](#about-speaker)


### Description

> How to understand human health across time or an individual self over a lifetime?

In this presentation and code, we look at time series analysis, a sub-field of machine learning and deep learning, using Python, and how it can be applied to tracking data like sleep and exercise from a FitBit, Apple Watch or Oura. 

While most often applied to financial, sales, and weather data, time series analysis is also important when we think about health and self data, because before we can start modeling we need to be sure we adjust for any temporal components (like trends, seasonality, or serial correlation). 

This talk and various code included provides a high-level yet actionable overview of time series analysis in Python. We look at tests for checking for temporal patterns (like Autocorrelation Plots and ADF) and time series techniques for normalizing or detrending time series data in certain situations. We examine classic time series statistical modeling using Box-Jenkins or ARIMA models, how to set parameters and see if it can be helpful for our health and self data. Finally, we do look at a range of other modeling approaches and ways interpret patterns and correlations between sleep and exercise over time. 

How to understand a self across time? Time series analysis allows us to look at non-stationary data like personal data, and translate that data into stationary data when needed. We can then look for patterns and meaning. It enables us to find relevant variables, plot recurring patterns and even make forecasts about trends in our health or productivity. Ultimately TS analysis becomes a powerful tool in the health analysis space for looking at how interventions (like a lifestyle change or treatment) have an impact on an individual (n=1) level. 

If we want to go beyond generic advice and personalize our medicine and healthy habits, we need to consider the tempoeral component and time series data analysis can help. 

### [Slides](https://markwk.github.io/ts4health/slides/slides.html)

- [View the most up-to-date slides here](https://markwk.github.io/ts4health/slides/slides.html). NOTE: Press "S" to view it in speaker mode and see additional talk notes and references. 
- [View Slides text in markdown](https://github.com/markwk/ts4health/blob/master/slides/slides.md).

### [Code](https://github.com/markwk/ts4health/tree/master/code)

- All Code: https://github.com/markwk/ts4health/tree/master/code
- [Data Visualization with Python on Health and Self Time Series ](https://github.com/markwk/ts4health/blob/master/code/Data_Visualization_Health_and_Self_Time_Series.ipynb) - Time Series Data Visualization using Fitbit or Apple Health Data for sleep and steps with primary focus being looking for trends, seasonality (esp day of week) and plotting autocorrelation function (i.e. lag). 
- Also see: [Time Series Data Visualization with Python](https://github.com/markwk/ts4health/blob/master/code/Time_Series_Data_Visualization_with_Python.ipynb) - a standard example of time series data analysis and visualization using temperature data. 
- [Tests and Techniques for Time Series Analysis on Health and Self Data](https://github.com/markwk/ts4health/blob/master/code/Tests_and_Techniques_Health_and_Self_Time_Series.ipynb) - Tests to check if there is a lag or other seasonality and various techniques to time adjust the data. 
- Also see: [Tests and Techniques for Time Series Data](https://github.com/markwk/ts4health/blob/master/code/Time_Series_Tests_and_Techniques.ipynb) - more general purpose code and examples for testing and adjust time series
- [Time Series Statistical Modeling for Health and Self](https://github.com/markwk/ts4health/blob/master/code/TS_Statistical_Modeling_Health_and_Self_Time_Series.ipynb) - applying Box-Jenkins or ARIMA TS modeling to our fitbit and apple health data to see if it helps. 
- Also see: [Time Series Statistical Modeling Forecasting](https://github.com/markwk/ts4health/blob/master/code/Time_Series_Statistical_Modeling_and_Forecasting.ipynb) - more generic code on ARIMA model for time series modeling weather data. 
- TODO: Final Analyss and Modeling for Health and Self Data: Having looked at temporal patterns and made the necessary adjustments, what can we learn from our data and how might we model it now? 

### Data

Data collection was done on a combination of wearables (Apple Watch, Fitbit, and Oura). Data aggregation was done using [QS Ledger](https://github.com/markwk/qs_ledger), an open source Python project for collecting and visualization of self-tracking data (Fitbit, Apple Health, Oura, etc). Each data set was then processed and aggregated into a standardized format. For additional information refer to [QS Ledger](https://github.com/markwk/qs_ledger) or see my previous speech [Python For Self-Trackers](https://github.com/markwk/python4selftrackers) for a walkthrough. 

Sample data is not being provided openly at this time. Please contact the author if you are in need of reference data or are interested in further data or analysis collaboration. 

### References

#### Published References

- Box & Jenkins. (2015). *Time Series Analysis*. John Wiley & Sons. (esp Ch 1-4)
- Pal. (2017). *Practical Time Series Analysis*. Packt Publishing Ltd. (esp Ch. 1-4)
- Downey, A. (2015). *Think Stats (2nd Edition)*. O’Reilly Media, Inc. (esp Ch 12)
- Velicer. (2012). *Time series analysis for psychological research*. Handbook of Psychology, Second Edition. (Thorough introduction to ts for social scientists)
- Aigner (2011). *Visualization of Time-Oriented Data*. Springer Science & Business Media. 

#### Internet Resources

- [Time Series Data Visualization with Python](https://machinelearningmastery.com/time-series-data-visualization-with-python/) - Code and example of data visualization for times series
- [A comprehensive beginner’s guide to create a Time Series Forecast](https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/) - nice walkthrough of techniques for time series analysis and transformations
- [ARIMA Model – Complete Guide to Time Series Forecasting in Python](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/) - good example of ARIMA modeling with step-by-step code from analysis and parameter setting in model to forecasting and model accuracy metrics. 
- [Time Series Analysis with Pandas](https://www.dataquest.io/blog/tutorial-time-series-analysis-with-pandas/) - uses Open Power Systems Data with some good examples
- [Pandas Time Series][https://ourcodingclub.github.io/2019/01/07/pandas-time-series.html] - pandas example using sunspots data
- [Playing with time series data in python](https://towardsdatascience.com/playing-with-time-series-data-in-python-959e2485bff8) - focuses on energy trends data and more deep learning methods
- [Working with Time Series from Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html) 

### About Speaker

TODO

