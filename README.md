# Stock Market Analysis and Prediction-Banks Stocks

### Introduction

In this project, Stock Market Analysis and Prediction will be performed for Four Canadian Banks, using data provided by Yahoo Finance. Pandas is used to get stock information, visualize different aspects of it, and finally perform risk analysis on the basis of its performance history. Also using the Monte Carlo method the future stock prices are pridicted.


### The Data

The data for this project has been obtained using pandas_datareader from Yahoo Finance. The symbols for four canadian banks namely The Toronto-Dominion Bank (TD), Royal Bank of Canada (RY), Bank of Montreal (BMO) and the Bank of Nova Scotia (BNS) were used and the data were obtained. 
 

### Tools Used

In this project python and its modules such as pandas, numpy, matplotlib, pandas-datareader, etc have been used. Monte Carlo method has been used to determine the value at risk for the stocks of these banks.

### Data Analysis and Visualization

Here the visualization results for TD stocks will be illustrated. For the complete visualizations and results of analysis please see the jupyte notebook.

Plotting the closing price during past year for TD stock data shows a drop in the closing price in March 2020 due to the COVID-19 pandemic.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/1.png">

Plotting the total volume of stock being traded each day over the past year for TD stock data shows that the volumne traded during the COVID-19 pandemic has also increased.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/2.png">

In the figure below different moving averages for TD stock data have been illustrated.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/3.png">

Also different Exponential Moving Averages for TD stock data have been shown in the figure below. Exponential Moving Averages react faster to the changes in the stock market.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/4.png">

Plotting the daily return percentage for TD stock data shows that the daily return fluctuated during the pandemic.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/5.png">

Plotting the closing prices for all four banks indicates that the closing prices for all these banks are fairly correlated.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/8.png">

The heatmap below shows the correlation coeeficients between the closing prices of different bank stocks.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/12.png">

Risk assessment for the stocks of all banks show similar risk for all of them.

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/13.png">

#### Monte Carlo analysis of TD bank stocks:

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/15.png">

<img src="https://github.com/kavehamini/Stock-Market-Analysis-and-Prediction-Banks-Stocks/blob/master/19.png">



### Conclusion

The stock market data for four Canadian banks has been investigated and analyzed. The risk for investing as well as future value at risk has been determined. All banks have relatively similar results.


### Author


This project has been inspired by many other similar projects and has been performed by Kaveh Amini (kvhmni@gmail.com).
