# BA-Project-Team3 🖐️
This is a team project that finds the relationship between renewable energy production and weather in each region of Spain and predicts appropriate prices according to the type of renewable energy by using data mining.

## 1. Topic description

![image](https://user-images.githubusercontent.com/66208800/201391151-8a332d2c-d1a0-49b2-ada5-8036e4907bbd.png)
+ The first goal of this project is to find a relationship between the weather climate such as snow, rain, wind, and temperature and the amount of renewable energy production by using weather dataset and energy generation dataset in Spain.

+ Then, the second goal is to predict electricity price for resale surplus power electricity. The factors are transportation fee, inventory fee, etc. My team will compare the predicted electricity price with TSO(Transmission Service Operator).

## 2. Problem definition
+ As concerns about climate change keep growing every year, nations across the globe are starting Carbon-zero plans for the next decade. Among their different goals, the increase of renewable energy production and consumption seems to be one priority of our generation. As opposed to fossil energy however, renewable energy such as solar or wind energy are not available all year and need specific weather conditions to be effective. Therefore, some countries may be more prone to some renewable energy than others. For example, countries near the equator might focus more on solar energy than Nordic countries as they get more direct sunlight throughout the year than the latter. However, it might be more complicated for countries with variable weather to decide which type of energy to invest in. Indeed, countries like Spain may want to invest both in solar and wind as well as other types of energy at the same time. As a result, an analysis of the location of the production and the time of the distribution is needed as the country wants as little as waste as possible and a cost as low as possible. This analysis will allow one to understand which energy costs the least and produces the most and therefore, decide which renewable energy to prioritize in the future. 

## 3. Purpose of the analysis

### 1) Why Spain? 
+ In Spain, the funding system for renewable energies is quite effective. The share of renewables in total power plant capacity was 44 % on 31 December 2013. The share of renewables in total power demand has increased from less than 7 % in 2000 to more than 25 % in 2013. Moreover, Spain has a variety of possible renewable energy production such as wind and solar energy thanks to its topography and weather. Therefore, we selected Spain, which uses more than 40% of renewable energy, as a target and conducted an analysis.

### 2) Our Purpose
+ Our purpose is not only to analyze the relationship between weather and renewable energy production, but also to **find the optimal real-time electricity pricing models appropriate price based on weather-related energy generation and consumption data**. Currently in Spain, only power transmission is under state control (REE, a state-owned enterprise), and power generation and distribution are operated by private companies.
We will use datasets for the energy, the weather, and the current Spanish TSO price (like SMP in Korea).
 
### 3) Our Constraints
+ Thus, our constraints are as follow:
  + 1) Our energy distribution policy considers only electric power transmissions from REE national power plants to substations of each company. 
  + 2) Loss of power due to distance is not considered.

### 4) Our Hypothesis
+ The price we predict could greatly enhance the profit of the entire region, rather than the price of electric energy under the TSO's current system.

### 5) Our Goal
+ Our ultimate goal in this project is to promote the development of renewable energy in the local market, to increase the acceptability of local renewable energy by presenting better policies than TSOs, and to respond to power peak times.

## 4. Dataset
![image](https://user-images.githubusercontent.com/66208800/201389294-62d6d354-0a2f-4778-b956-7f6c11b88815.png)
+ *energy_dataset*

![image](https://user-images.githubusercontent.com/66208800/201389344-81317727-21da-42d1-b9c8-14b9d3cfca39.png)
+ *weather_features_dataset*

+ As for the datasets that will be used for this project, we found two main datasets on Kaggle uploaded by Nicholas Jhana that were last updated in 2019. In the former one, we have features about the energy consumption and production in Spain by the hour as well as the overall price of the energy. In the latter one, we have information about the weather in 5 cities in Spain such as Barcelona and Valencia and their respective temperature, rain, etc. 
