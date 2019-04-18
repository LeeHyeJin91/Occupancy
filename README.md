# Data science portfolio by HyeJinLee


# Occupacny: *Occupacny Prediction*

This notebook is my rerport for Occupacny Prediction. In this project, I concentrate on <U>*logical flow for creating new features* </U>.   
The dataset is from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+).


## Description
The goal of this project is to predict whether or not a room is occupied based on environmental measures such as temperature, light, CO2 and so on.


##  Data
Occupacny data is divided into three files, one for training and the others for testing. In train file, a column 'Occupancy' shows whether there are one or more people in a room (0 for not occupied, 1 for occupied). The occupancy has been measured every minutes and train file covers a week's worth of data.


## Problems of Occupacny Prediction

#### 1. Time series data
As this dataset is timeseries, it is important to discover the pattern of each feature over time. 

#### 2. The ambiguity of continuous feature
There exists the case that some continuous features have the same values in both cases (Occupancy=0 and Occupancy=1). As a result, the machine(our model) can't distinguish where these values belong to. So I made the machine discern these values by creating some features. I explained this part in ***3.3.4*** of notebook concretely.  

#### 3. Visualization


## Notebook

[Github](https://github.com/LeeHyeJin91/hyejin/blob/master/Notebook/Occupancy.ipynb) [nbviewer](http://nbviewer.jupyter.org/gist/LeeHyeJin91/173361ea3ff40e9b9db6f6be07334b71)

