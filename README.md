# Time-series-guided-dashboard-analysis-with-knime

### Problem statement: You are given 5 years of store-item sales data, and asked to predict 3 months of sales for 50 different items at 10 different stores.

* We have taken 4 years of product sales dataset from kaggle which contanins historical sales records of 10 stores and 50 products, from the year 2013 through 2017.

* For the purpose of this task , we will only look at the sales of 'item'  1 from store 1.

* you can deploy this to knime sever and use this workflow for a guided analytic forecasting

* In knime analytics platform itself, you can click right on any component and click on Interactive view, to see dashborad view.




### In this workflow we have taken grocery dataset for 10 stores contains data for 50 different items. This workflow can be deployed for a guided analytics webportal, i.e. easy to use dashborad for time series inspecction and forecasting.

Steps:

* Data preparation: data loading, data exploration, data imputation

* Selecting parameters and filtering data: selcting particular store, item , setting parameters for weekly/monthly stats visualizations

* data visualizations: data inspection , weekly/monthly sales

* seasonality inspection: seasionality inspection, seasonality removing, lag preparation

* model training and evaluation: traing model on time series data, matics evaluation, line plot for performance
