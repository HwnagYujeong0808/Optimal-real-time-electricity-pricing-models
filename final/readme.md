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
 + Use Linear, Ridge and Lasso model but the r2_score difference of fossil and renewable is small
 + ∴ Determine to use XGBoost and Random Forest model
 + 
