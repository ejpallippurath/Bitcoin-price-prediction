## bitcoin-price-prediction

### Objective
The aim of this project is to develop an AR (Autoregressive) model to predict the future price of Bitcoin based on its historical data. The model will be trained on a dataset containing Bitcoin's price and date for each trading day, and it will learn the patterns and trends in the data to predict the price for the next few days or weeks.

### Dataset
The dataset used for this project will consist of historical data of Bitcoin's price and date for each trading day. The dataset obtained from financial data providers as csv file.

### Modeling
The AR model is a statistical model used to predict future values based on past values. It is a time-series model that takes into account the previous values of the same variable to make predictions for the future. In this project, we will use the AR model to predict the future price of Bitcoin based on its past prices.

The model will be trained on a training set and validated on a testing set. The data will be preprocessed to remove any missing or inconsistent values, and then the model will be trained using the training set. The model's performance will be evaluated on the testing set using metrics like mean absolute error (MAE).

### Visualization
Once the model is trained and validated, we can visualize the results using graphs and charts. We can plot the actual and predicted Bitcoin prices over time to see how well the model is performing. We can also plot the residuals to check if the model is capturing all the relevant information in the data.

![wfv](https://user-images.githubusercontent.com/84701560/229135472-11cddb6a-12d4-4ff8-9e6f-79c98af57162.png)

### Conclusion
Bitcoin price prediction is a challenging problem due to its highly volatile nature. However, by using the AR model, we can predict Bitcoin's future price with reasonable accuracy based on its past prices. The project will provide insights into the dynamics of Bitcoin's price and can be extended to other cryptocurrencies or financial assets.

