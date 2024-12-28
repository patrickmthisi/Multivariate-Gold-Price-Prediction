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
