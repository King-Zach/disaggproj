## Energy Disaggregation

---
### Problem Statement
**We should predict single or multiple appliance energy consumption for a house based on total power consumption of the house 
to facilitate this we are also using factors like temperature, humidity & pressure**

### Data

Dataset can be downloaded from [kaggle](https://www.kaggle.com/loveall/appliances-energy-prediction)

There are 29 features in KAG dataset:

some key features are:

- date : time year-month-day hour:minute:second
- lights : energy use of light fixtures in the house(which is target for this specific problem)
- Temperature in living room area, in Celsius
- Temperature outside (from Chievres weather station), in Celsius
- Pressure : (from Chievres weather station), in mm Hg
- Wind speed: (from Chievres weather station), in m/s
- Visibility :(from Chievres weather station), in km
- Appliances : Total energy consumption in Wh


### Data Visualization:
---
![alt text](images\newplot.png "timeseries beahviour of total consumption")

![alt text](images\univariate.png "univariate analysis plots")

![alt text](images\totalenergydistplot.png "total energy consumption distribution plot")

### Data Modelling
Tried sklearn's regressors and got following scores:

![alt text](images/evaluation%20of%20varios%20models.jpg "evaluation on various model")

here Extra tree regressor is performing well

### Scope of improvement

Deep learning techniques may improvise it further.





