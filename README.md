# Time Series Analysis of Building Energy Data

Building L is an academic building for a university in California. For such building types, energy consumption is typically accounted for by lighting systems and heating, ventilation and cooling (HVAC) systems. For this project, I was interested in using Python to develop a model to predict a building's energy consumption based on data that are usually publicly available such as outside air temperature. In addiiton, depending on building type and building use, there are generally also noticeable pattern such as seasonality. For example, in the summer, when the outside air temperature is higher, air conditionining systems which are electric-powered are operated more to maintain a certain setpoint. In the winter on the other hand, when the outside temperature is lower, heating systems, which are generally gas-powered, are operated to maintain a certain setpoint.

Thus, in general, we would expect to see higher building energy consumption during the summer in comparison to the winter.

Through this project, I explored the concept of stationary data, the transformation of data, the use of Seasonal Autoregressive Integrated Moving Average (SARIMA) model and how to incorporate an exogenous variable to improve model performance.


<img width="1319" height="627" alt="building energy use prediction" src="https://github.com/user-attachments/assets/2b111f11-ec84-4166-bff3-3d6c0a50ad5b" />
