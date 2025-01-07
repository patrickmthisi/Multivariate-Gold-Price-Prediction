# Multivariate-Gold-Price-Prediction
## Project description and objectives:
The dataset consists of gold prices. For more information  about the data used in this project, refer to:

https://www.kaggle.com/datasets/sid321axn/gold-price-prediction-dataset.

In this end-to-end project, we develop and compare two multivariate time series models: the multi-head ConvLSTM model and the multichannel CNN-LSTM model for forecasting gold prices. The following essential concepts are explored in this project:
1. Multivariate deep learning models, specifically the multi-head ConvLSTM and multichannel CNN-LSTM models, are used to forecast gold prices. An automated search of historical data is performed using a novel hybrid approach that combines random search (for broad exploration) and Bayesian optimization (for refined search) to identify the optimal parameters.
2. Automated Explanatory Data Analysis using pandas profiling.
3. Rolling Forecast: 
    - Once each model is fitted, a rolling forecast method is applied, allowing for predictions to be made one step ahead. The model is updated iteratively using actual values.
4. Model Evaluation:
    - The predicted values are compared to the actual values from the validation set.
    - The Root Mean Squared Error (RMSE) is the metric to assess the model's performance.    
5. Conclusion: The study concludes with a quick review of the performances observed in this project and a comparison to the performance of the univariate case, which was investigated in another related project that we completed.

## Conclusion
This project builds upon the insights gained from a previous project where we employed a univariate time series model to forecast gold prices. In this multivariate approach, we integrate additional financial features, including stock indices and currency indices. It is commonly observed that there is a negative correlation between gold prices and financial indices such as the S&P 500 Index and the Dow Jones Index. This phenomenon aligns with the concept of "flight to safety," which occurs during periods of market turbulence as investors gravitate towards safer investments, typically gold. In this end-to-end project, we explore the application of advanced machine learning techniques, specifically the multi-head ConvLSTM and the multichannel CNN-LSTM models, to forecast gold prices by integrating a variety of relevant market variables. Our findings show that the multi-head ConvLSTM model delivered superior predictive performance compared to the multichannel CNN-LSTM model, achieving an RMSE score of 0.372. In contrast, the multichannel CNN-LSTM model recorded an RMSE of 0.407. Notably, both of these models fell short of the accuracy demonstrated by the univariate CNN-LSTM model, which stood out with an impressive RMSE score of 0.308, highlighting its effectiveness in price prediction within this context.
