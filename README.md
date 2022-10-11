
# Air-Passengers-Time-Series-Analysis

* In this project, I want to check if the air passenger data is seasonal, which can help with developing future bussiness strategies for companies serving the tourism industry. 
#### Objectives:
- Understand the Dataset & cleanup (if required).
- Perform the necessary checks like stationarity & DF on the Dataset.
- Build a forcasting model to predict the future volumn of the air passengers.


## Acknowledgements

 - [This dataset is referred from Kaggle](https://www.kaggle.com/datasets/chirag19/air-passengers)
 - This dataset provides monthly totals of a US airline passengers from 1949 to 1960. This dataset is taken from an inbuilt dataset of R called AirPassengers.
 


## Dataset Features and Description

- A simple yet challenging project, to forecast the volume of air passengers, based on monthly totals of a US airline passengers from 1949 to 1960.
Can you overcome these obstacles & Forecast the future occupancies of the Airlines?

This data frame contains the following columns:
* `Month` : The month of observation.
* `Passengers` : Total Passengers travelled in that particular month.

## Code and Resources Used

- **Python Version** : 3.8
- **Packages** : pandas, numpy, statsmodel, scipy, matplotlib, seaborn, sklearn.

#### Methods and Tools
- Python
- Advanced Excel
- ARIMA
- Augmented Dickey-Fuller Test
- ACF and PACF
- Statsmodels


## Strategic Plan of Action:
1. Import Libraries needed.
2. Import dataset and display head records, columns and basic information.
3. Visualize the time series - Check for trend, seasonality, or random patterns.
4. Stationarize the series using decomposition or differencing techniques.
5. Plot ACF/PACF and find (p,d,q) parameters.
6. Building the forecasting model - can be AR, MA, ARMA or ARIMA.
7. Making Predictions using the Forecasting Model.



## Screenshots
### TimeSeries Plot for Dataset
![TimeSeries Plot](https://user-images.githubusercontent.com/109909092/195176810-3708a885-c3d0-4a62-8d99-1e0e9cd76f4a.jpg)

### Stationary Check Plot
![Stationary Check Plot](https://user-images.githubusercontent.com/109909092/195177461-bd9cb1ab-d11d-4182-95aa-6ff597bee02d.jpg)

### Decomposing using moving average
![Decomposing using moving average plot](https://user-images.githubusercontent.com/109909092/195179739-bdbc11c3-2b31-4009-b5fb-2328a58c58ce.jpg)

### Stationary Check for Decomposed Time Series
![Stationarity Check for Decomposed Time Series plot](https://user-images.githubusercontent.com/109909092/195177800-1ad4fbd3-f52d-4946-a716-f22ac50efde1.png)

### ACF Plot 
![Auto Correlation Fuction plot](https://user-images.githubusercontent.com/109909092/195178731-c3f88866-babe-4268-8e8b-5d28af2e2058.jpg)

### PACF Plot
![Partial Correlation Fuction plot](https://user-images.githubusercontent.com/109909092/195179074-35cf9088-94ac-4f54-9e2a-a977602a58d9.jpg)

### Original vs Forecast Plot
![Original vs Forecast plot](https://user-images.githubusercontent.com/109909092/195180066-85031553-a9ac-4de2-a197-643870ad468f.jpg)

### Final Forecasted Plot
![Final Forecast plot](https://user-images.githubusercontent.com/109909092/195180192-bf7644e9-d293-4dc1-8f23-df71a2b785c2.jpg)
## Project Outcomes & Conclusions

#### Here are some of the key outcomes of the project:
- The Air-Passengers Time-Series Dataset was quiet small, with just 144 samples.
- It was clear from the visuals that the time-series dataset had an upward trend & some seasonality.
- The same was confirmed with help of visual (rolling mean & std) & statistical (Dicky-Fuller Test) stionarity checks.
- The time-series was subject to Decomposition in order to stationarize the outputs.
- Futher ACF & PACF curves were plotted to extract the values of p & q, as it is required for the ARIMA Model.
- The Forecasting Model was then built with the time-series data, by feeding the optimal p,q,d values.
- Finally, the model was used to forecast the time-series of the air-passengers, into the future.

