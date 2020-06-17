# Future_Price_Prediction_of_Products
I have made a future price prediction model using Facebook Prophet. Here I've used the avocado price dataset of USA.


Facebook Prophet is an open source tool used for time series forecasting. <br/>
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.<br/>
Prophet works best with time series that have strong seasonal effects and several seasons of historical data. 

<br/><br/><br/>
### Prophet implements an additive regression model with four elements:
<br/>
1. A piecewise linear, Prophet automatically picks up change points in the data and identifies any change in trends.  
<br/>
2. A yearly seasonal component modeled using Fourier series.
<br/>
3. A weekly seasonal component.
</br>
4. A holiday list that can be manually provided.
<br/>
<br/>
Reference: https://research.fb.com/prophet-forecasting-at-scale/








<br/><br/><br/>
In this project I've predicted the future price of Avacados in entire USA as well as region wise.<br/>
For this I've used the avacado dataset which had data collected from 2015 to 2018. Following is the result of the model.



<br/>
<br/>

## Future prediction of price in entire USA.
![Screenshot (336)](https://user-images.githubusercontent.com/57986361/84913293-02864580-b0d8-11ea-9a01-2d7abbfe0db2.png)

Here the black dots represent the price associated at particular time and the region containing these dots is our history of prices.
The graph further tells the predicted price of the product. As we can see the future price in entire country will decrease in the next year. This prediction is very helpful as it tells the future demand for the product and helps in pre availability.

![Screenshot (337)](https://user-images.githubusercontent.com/57986361/84914908-ca800200-b0d9-11ea-86c9-2f1b445271b6.png)

The above graph shows the trend of the product according to time. This clearly shows the decrease in trend which results in price drop of product as predicted by the model.

<br/>
<br/>

## Future prediction of price (region specific)
![Screenshot (338)](https://user-images.githubusercontent.com/57986361/84915476-79bcd900-b0da-11ea-9688-b1ee969c5d0b.png)

<br/>.Above is the price prediction of only Chicago. We can see that the price of the product increases in this case.

![Screenshot (339)](https://user-images.githubusercontent.com/57986361/84915495-7e818d00-b0da-11ea-85df-f0aab8d8da03.png)
<br/>This graph shows the trend of the product is increasing in upcoming time.




<br/>
<br/>
<br/>
<br/>
This project includes the use of Facebook Prophet at its core. For further details on the mathematics behind this Prophet model visit:
<br/>
1. https://research.fb.com/prophet-forecasting-at-scale/
<br/>
2. https://facebook.github.io/prophet/docs/quick_start.html#python-api
