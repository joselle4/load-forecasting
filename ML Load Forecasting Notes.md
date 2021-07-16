3 Load Forecasting Categories:
1. STLF - short-term load forecasting; ranging from a few hours to a few days
2. MTLF - medium-term load forecasting; ranging from a few days to a few months
3. LTLG - long-term load forecasting; greater than or equal to one year

Models
1. ARMA or Autoregressive Moving Average - mean absolute percentage error (MAPE) of 9.13%
2. SARIMA or Seasonal Autoregressive Integrated Moving Average - MAPE of 4.36%
3. ML LSTM or Long Short-Term Memory models - MAPE of 1.975% 

Load Forecasting
- curve fitting methods do not provide accurate results per models 1 and 2 above
- ML algorithms are better at dealing with complex multi-variable and multi-dimensional estimation problems
- Parameters: time of day, previous electricity demand trends, weather, humidity, electricity price, etc.
- can also use past energy trends, correlated with weather data and a timestamp for predictions

Neural Networks
- an artificial neural network is a layered structure of connected neurons
- combination of various algorithms which allow us to do complex operations on data

Recurrent Neural Networks (RNN)
- a class of neural networks tailored to deal with temporal data
- the nuerons have a cell state/memory and input is processed according to this internal state, which is achieved with the help of loop within the neural network

LSTM Models
- a class of recurrent neural network that is capable of long term dependencies in data
- achieved because the recurring module of the model has a combination of four layers interacting with each other
- critical to load forecasting since adding too many layers and hidden nodes can quickly lead to overtraining which performs exceptionally well on training data but not real-world scenarios while too simple a system adn you would end up with below average forecasting for both training and test data

Sources:
- https://valohai.com/blog/smart-grids-use-machine-learning-to-forecast-load/
- https://www.tutorialspoint.com/time_series/time_series_lstm_model.htm#:~:text=Time%20Series%20-%20LSTM%20Model%201%20Neural%20Networks.,capable%20of%20learning%20long%20term%20dependencies%20in%20data.
