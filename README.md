# CDC Covid-19 Vaccination Data Analysis with SARIMAX Forecasting
## Project Description
Took the CDC covid-19 vaccination data and did an analysis on the vaccination rates of the total population as well as the age groups 12+, 18+, and 65+. Then I preceded to look at the vaccination rates of each state, and created choropleth maps showing the vaccination rates over time in the United States, down to the individual counties. This was done with the total population, as well as the three age groups mentioned previously. Then I created a Seasonal AutoRegressive Integrated Moving Averages with eXogenous regressors (SARIMAX) forecasting model for forecasting the vacination rate growth of the total population, as well as created a forecasting model for each state/territory that featured vaccination percentage data.
## Programs and Packages Used
Program: Python 3.8.5<br/>
Packages: numpy, pandas, statsmodels, matplotlib, seaborn, plotly, datetime, urllib, json
## Running the Project
Some the cells have been commented out due to long outputs, or causing the file size to increase dramatically (Choropleth Maps), but please feel free to run them on your local machine so see the visualizations/outputs. In terms of the parameters of the SARIMAX model, due to hardware constraints, the highest I could go was (0,3) for total population, and (0,2) for state, so please feel free to modify these parameters if your machine can handle it.
## Credits
Data: https://www.kaggle.com/tunguz/covid19-vaccinations-in-the-united-states-county<br/>
Data Dictionary: https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh<br/>
SARIMAX Guide: https://www.digitalocean.com/community/tutorials/a-guide-to-time-series-forecasting-with-arima-in-python-3
