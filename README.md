# Forecasting Electricity by Hour 
## About Dataset

Hourly Electricity Consumption and Production by Type in Romania for 5.5 years.
It includes the hourly consumption and production, and the production is split into one of the categories: Nuclear, Wind, Hydroelectric, Oil and Gas, Coal, Solar, and Biomass.
When the production is greater than the consumption it means we are exporting electricity, when the value is smaller it means we are importing electricity.<br>
All values are in MWs.<br><br>
**Objective**: Explore the Production and Consumption of Electricity produced by different types of energy sources and build an RNN and LSTM to forecast them <br>
**Methods Used**: Exploratory Data Analysis, time series analysis,  Data Visualization, deep learning, Predictive Modeling .<br>
**Type of Problem**: Multivariate Regression.<br>
**Language, Libraries, technologies used**: Python, Pandas, Matplotlib, Seaborn, Numpy, Scikit-learn, TensorFlow, Keras <br>
## Key Insights
- I first loaded and Displayed the Dataset and then created the plots to explore the dataset and gain insights about ELectricity Consumption. Here are some Insights:
  - The country imports a little more electricity than it exports.
  - On average 1291 Mws of nuclear energy is produced per hour.
  -  In 2023, 32.4% of electricity production was hydroelectric.
  -  Hydroelectric and Nuclear have a Negative Correlation meaning when the production of one is increasing the second decreases
- Then I apply the RNN na LSTM to forecast Electricity production and consumption.
- Both of this gives amazing results but the LSTM performs slightly better with a coefficient of determination of 0.98 on Consumption and 0.96 on Production than the RNN.

