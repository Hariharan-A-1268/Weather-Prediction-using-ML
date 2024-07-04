#   **Real Time Weather Prediction Using Machine Learning**
This project uses a machine learning model to predict the weather for the next five hours and gives the current weather data of your area. With the predicted data the model gives information, whether to irrigate your agricultural field. It also contains some information related to some efficient irrigation methods that will be helpful for farmers.

For data collection, we use Open-Weather API to get the hourly data of past 48 hours and predict the temperature and humidity for next 5 hours of the given place. The website also displays the current weather conditions of the same place.

For weather prediction the model uses a popular Time-series Forecasting algorithm called ARIMA (Autoregressive Integrated Moving Average). This model is a combination of the Auto Regression (AR) model and the Moving Average (MA) model. 


> Machine Learning Model

*ARIMA models are generally denoted as ARIMA (p,d,q)  where p is the order of autoregressive model, d is the degree of differencing, and q is the order of moving-average model. ARIMA models use differencing to convert a non-stationary time series into a stationary one, and then predict future values from historical data.*

> Frontend

In Frontend, we have used HTML for webpage structure, CSS and Bootstrap for styling the webpage, Chart.js for plotting the graphs.

> Backend

In Backend, we used Python framework called Flask to process the machine learning model and build the webpage.

> API

openWeather API

![image](https://github.com/Hariharan-A-1268/Weather-Prediction-using-ML/assets/120185640/7501b422-7171-4e50-890f-6ffc716794fa)
![image](https://github.com/Hariharan-A-1268/Weather-Prediction-using-ML/assets/120185640/324882f3-056f-4089-8726-82708dc011fa)
![image](https://github.com/Hariharan-A-1268/Weather-Prediction-using-ML/assets/120185640/a07f0076-2fca-4ed5-bdfa-16b1ea6acd02)
![image](https://github.com/Hariharan-A-1268/Weather-Prediction-using-ML/assets/120185640/1d498e49-d41e-4fef-afa9-7907357aae16)
![image](https://github.com/Hariharan-A-1268/Weather-Prediction-using-ML/assets/120185640/a2f8645b-13df-4196-997d-5f0593457283)




