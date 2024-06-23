# CSP_DA24C3 
Work on simple capstone project on Time-Series theme on household power consumption prediction.

Dataset: https://www.kaggle.com/code/vedumrajkar/electricity-consumption-time-series-analysis/notebook

This dataset contains six months of household electricity consumption data, gathered between January 2007 and June 2007

Dataset information:

Date: The date of the observation. (Date)
Time: The time of the observation. (Time)

Global_active_power: The total active power consumed by the household (kilowatts). (Numeric)
Global_reactive_power: The total reactive power consumed by the household (kilowatts). (Numeric)

Voltage: The voltage at which the electricity is delivered to the household (volts). (Numeric)
Global_intensity: The average current intensity delivered to the household (amps). (Numeric)

Sub_metering_1: The active power consumed by the kitchen (kilowatts). (Numeric)
Sub_metering_2: The active power consumed by the laundry room (kilowatts). (Numeric)
Sub_metering_3: The active power consumed by the electric water heater and air conditioner (kilowatts). (Numeric)

Notebook order
1)LT Part 2 Problem Statement and Dataset
2)1_Exploring_Dataset_Power_Consumption
3)2_ARIMA_modelling
4)3_SARIMAX_modelling

Stages of project:

1) Understanding project

what is the topic: power consumption
what is the goal: predict power usage in next years to come

2)Understanding the data

Load the data, the info and the points for each features in the data

3)Data preparation

Dataset would be cleaned,organized and munging so that it fit with the obejctive and analysis

My medium post on what i learn from EDA my data:
https://medium.com/@pillowkuat/what-i-learned-from-exploratory-data-analysis-eda-of-my-dataset-1b8e72262ea1

4)Data modelling

As the dataset has been cleaned and formatted to be appropriate for modelling, we will proceed with time-series analysis using ARIMA and SARIMAX on the dataset.

5)Model Evaluation

As the dataset is trained and forecasting prediction on the test set, we will evaluate the model based on the error.

6)Deployment

The model will be deployed by reporting and presenting to the stakeholders.

My medium post on my capstone project: https://medium.com/@pillowkuat/predicting-household-power-consumption-with-time-series-analysis-an-arima-model-tutorial-5d7f83b71e88


