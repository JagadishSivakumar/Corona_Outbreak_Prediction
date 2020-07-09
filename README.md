# Corona Outbreak Prediction in India

### Overview
The idea of the project is to develop an effective time series additive model and answer "Will India become next Italy, Wuhan, S.Korea ? ". The dataset used in the project is from Government Websites, Time Series - John Hopkins updated Git. The latest version of dataset is available in Kaggle - [COVID -19 in India](https://www.kaggle.com/sudalairajkumar/covid19-in-india)

The dataset used in my project is also provided in the respository. I have used Google Colabs for the time-series prediction of Covid-19 trend in India.

### Initial Spread of Corona Virus in India
- 30th Jan , a student from Wuhan
- 2nd March , 6 cases
- 4th March , 32
- First 100 Cases on 14th March

As of 3rd May - 39,980 Cases & 1301 Deaths

### Sudden Rise of confirmed cases in between Fed 12 - 15 in India
The Research body - cameup with new way of calculating Corona affected patients. Thus a massive increase in count on 13/02.

### Facebook Prophet
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
- Shift in trend with missing data
- Handles outliers well
- Fully automatic and tunable

### Predictions 
- Confirmed cases, Deaths, Recoverd with latitude and longitude details of locations are provided in the dataset. The dataset has entries available till 23rd of March
- With time-series based additive model, Facebook prophet the predictions of confirmed cases, death and recovered cases are done till 30th of March

**Worldwide Confirmed Cases**

![Dipinwed](https://github.com/JagadishSivakumar/Corona_Outbreak_Prediction/blob/master/Predictions/confirmed%20-%20worldwide.png)

The dip in wednesday - On analysing dataset, there was a huge dip in China on Wednesday

**Death Forecast**

![deathforecast](https://github.com/JagadishSivakumar/Corona_Outbreak_Prediction/blob/master/Predictions/death.png)

**Recovered cases**

![recoveredcases](https://github.com/JagadishSivakumar/Corona_Outbreak_Prediction/blob/master/Predictions/recovered%20-%20prediction.png)

### Conclusion
- Most number of recovered cases are on Sunday, Monday
- Most number of confirmed cases are also on Sunday and Monday

**Will India become Next Italy, South Korea , Wuhan ?**
Yes, if we look at the world's data and its forecast we can say India might face one of its worst days. Thus, Strict Lockdown must be implemented to overcome spread of Disease and stabilize the curve.

**India is in the second stage of coronavirus as of Mar 29th and is 145th position worldwide**

In India, The fatality is predicted to be only 2% of affected crowd but the forecasted crowd is about `60%` of world population.
