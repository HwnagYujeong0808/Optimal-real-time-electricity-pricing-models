## Final presentation
 
###  Topic
 + Find any problem that can be solved by data mining techniques in one of business domains whatever.
 + Specify the problem in business areas
 +  Specify the goal and purpose of your project
###  Data
 +  Collect data related with the problem
 +  Two or more datasets from different sources or different domains should be used
   + Ex) weather data and highway usage statistics
 +  Specify the target in the case of supervised learning
###  Method
 +  Apply appropriate preprocessing steps
 +  Specify the approach related with data mining to solve problem or achieve goal
 +  Find the best model you can get
###  Result
 +  Obtain experimental results from your models
 +  Compare different models
###  Discussion and conclusion
 +  Interpret your results
 +  Provide the main finding
 +  Provide solutions of the problem
 +  limitation and future work

### ‼️ We have to focus on 
 + **Modeling & evaluation**

## Specific

### Make model and evaluation

#### Season feature
 + Compare whether the season feature is used or not
 + Output is actual price and training models are Linear, Ridge and Lasso regression
 + When 'season' feature is used, the performance is improved

#### Fossil energy & Renewable energy
 + The correlation of attributes related to fossil energy was high
 + Split fossil energy dataset & renewable energy dataset
 + Use Linear, Ridge, Lasso, XGBoost and Random Forest model
 + XGBoost and Random Forest model: To compare accuracy, hyperparameter tuning and no hyperparameter tuning are used
 + In hyperparameter tuning, random search is used instead of grid search for speed and ordinal encoder is better than one hot encoder due to performance
 
 #### Evaluation results
  + When comparing r2_score, renewable energy is generally larger than fossil energy
  + In renewable energy dataset, wind_speed, pressure and generation solar are important features
  + In fossil energy dataset, weather data and generation of energy data have a significant impact on predicting actual price
  + We need to consider the other model(ARIMA), because the previous models have rather low accuracy

### Alternative(ARIMA)
  + Determining whether the time series is stationary or not with the Augmented Dickey-Fuller test.
  + Make the time series stationary and find the ARIMA parameter d
  + Do the ACF and PACF plot and find the parameters p and q
  + ACF plot is sinuosidal so we can use the ARIMA(p,d,0) model
  + Build the model and predict a forecast
  + Do it over different timespan: the ARIMA model is good for 1 and a half week
  + We need to update it regularly !

### Conclusion
 + By considering R2 score, MSE and MAE, To best predict energy prices, we need to use a XGBoost MODEL in renewable energy dataset.
 + The model predicted prices better when considering renewables energy production data such as solar energy and biomass
 + The added feature 'season' impact positvely the price predictions
 + The R2 score is as low as 0.55 which means Spain does not produce enough renewable energy
 + The price decreases the more renewable energy is used
 + Additional datasets with features such as stock prices should be used in future work

