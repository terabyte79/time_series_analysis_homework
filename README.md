# time_series_analysis_homework

## The purposes of this assignment is to find answers to the following questions using timeseries analysis. Sales and revenue forecasting for the company will be done using 'Prophet'.

1. Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
2. An evaluation of how the company stock price correlates to its Google Search traffic.
3. A Prophet forecast model that can predict hourly user search traffic.
4.  A plot of a forecast for the company’s future revenue.


## Findings 

1.  Did the Google search traffic increase during the month that MercadoLibre released its financial results?

 *  Yes , the median traffic was 35172.50 whereas in the month on May 2020 it rose to 38181.

 2.  Does any day-of-week effect that you observe concentrate in just a few hours of that day?

* Yes, traffic is very less from 5.00am to 12.00pm and as the day progress it increases and is at the highest during 10pm-12am . This trend can be observed throughout all days of the week.

3. Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

* Yes, the search traffic definitely increases during the winter holiday period.

4. Do both time series indicate a common trend that’s consistent with this narrative?

* Yes, during the initial months of Covid, which were March 2020 and early April 2020, the search trend was low, which was reflected in stock prices as well. However, by late April to early May, the search trends spiked, and the stock price also increased in the following months. The stock price reached 984.93 by the end of June, representing around a 63.84% increase compared to its opening value in January.

5. Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

* The relationships between lagged search traffic and both stock volatility and hourly stock returns are very weak and not particularly predictable. The correlations are close to zero.

### Popularity Forecasting using Prophet 
6. How's the near-term forecast for the popularity of MercadoLibre?

* The popularity seems to be trending downwards in near tearm future.

7. What time of day exhibits the greatest popularity?

* Midnight - 12.00am

8. Which day of week gets the most search traffic?

* Tuesday

9. What's the lowest point for search traffic in the calendar year?

* In the month of October

### Revenue Forecasting using Prophet 

10. Based on the forecast information generated , produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.

* Based on the forecast information , below are the best , worst and most likely sales forecast for the next quarter for the company. (in million dollars USD)

* Best_case = 1051.37(millions USD)
* Worst_case = 888.23(millions USD)
* Most_likely = 969.61(millions USD)