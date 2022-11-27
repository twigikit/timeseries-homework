# timeseries-homework

This exercise requires using Google Colab to produce a Jupyter notebook that contains data preparation, analysis (including predictive modelling) and visualisations for all the time series used.

Key objectives of the exercise are:
* Identify patterns in the time series data. We look at three set of time series data: <br>
1. Google hourly search trends on Mercado Libre from 2016-2020 <br>
2. Mercado Libre hourly stock prices from 2015-2020 <br>
3. Mercado Libre daily sales revenue from 2019-2020 <br>

* Mining for patterns in seasonality by using visualisations <br>
* building sales-forecast and user-interest predictive models by applying a Prophet forecasting model to the data.

## Findings
### Unusual Patterns in Hourly Google Search Traffic
Mercado Libre announced its first quarter 2020 financial result on the 5th May 2020. On the result announcement day, the number of google search traffic on the company is significantly higher than usual. 
![](./Diagram/202005_googlesearch_plot.png)

When comparing the total search traffic May 2020 (33101) to the monthly median across all the months (33896), there is no unusual pattern identified. 

### Mine the Search Traffic Data for seasonality
### Day of the week
![](./Diagram/averaga_search_traffic_dayofweek.png)
From the average search traffic by the day of week, we tend to see high search traffic between Tuesday to Thursday and low search traffic on the weekends. 

![](./Diagram/heatmap.png)
From the heatmap, we can further observe the searches are concentrated between hours 22-23 and hours 0-1 of the day.

#### Week of the year
![](./Diagram/search_traffic_weekofyear.png)
During the winter holiday period (weeks 40 through 52), there is an obvious increasing trend between week 42 through 48 and followed by a decreasing trend.
