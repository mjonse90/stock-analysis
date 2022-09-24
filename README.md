# stock-analysis

## Overview of Project

The purpose of the project was to run analysis on green energy stocks. The client's request is to run an analysis to better help recommend stock buys and sells. Total daily volume and return analysis were conducted for the years 2017 and 2018.

An original VBA script was developed, but with the ability to only analyze 12 stocks. In order for the client to be able to analyze a greater number of stocks, the code was refactored. After refactoring, the client is now able to analyze a greater number of stocks.

## Results

### 2017 Stocks

<img width="616" alt="Screen Shot 2022-09-24 at 1 05 48 PM" src="https://user-images.githubusercontent.com/103767830/192112526-502a5b26-3c8b-4943-831c-14d3fb5f5ed4.png">

According to the analysis, 2017 had an overall positive return on all stocks except for TERP which saw a loss of -7.2%. The most successful return was with DQ which saw a +199.4% increase, followed by SEDG with a +184.5% return and ENPH with a +129.5% return.

### 2018 Stocks

<img width="616" alt="Screen Shot 2022-09-24 at 1 06 16 PM" src="https://user-images.githubusercontent.com/103767830/192112531-8f34c56d-d875-4838-ae5f-cf309153d2cc.png">

2018 saw a much larger loss across all stocks compared to the 2017 analysis. The only stocks that saw an increase were ENPH with a +81.9% return and RUN with a +84% return. A couple of stocks saw marginal losses. For instance, AY (-7.3%), SEDG (-7.8%) TERP (-5%) and VSLR (-3.5%). While other stocks saw significant losses such as DQ (-62.6%), JKS (-60.5%), and SPWR (-44.6%). 

For both years, times improved by about half a second when the code was refactored.

## Summary

With refactoring the code, times improved by around half a second. Which may not sound like a lot. But compounded over time, adds up to a lot of valuable time for the client. By refactoring the code, the improved functionality of the analysis improves and becomes more efficient, which is an overall bonus for all involved with the process.

A disadvantage of refactoring code is that it is a time consuming process. Something that would have to be brought to the client's attention to see if (in our case) the half second improvement is worth the time it took to refactor the code.
