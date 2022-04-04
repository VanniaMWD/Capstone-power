# Electric Power Generation in Canada 1950-2007

## Description

Time series forecast of Electric Power Generation in Canada from 1950 to 2007. It has the objective, 
to estimate the generation capacity in Canada. 

How much expensive will be to consume/produce electricity? How much will cost to produce electricity? 
Industry and Businesses must know how much capital to allocate for energy consumption for their production. Equally important, they can determine the cost of their products or services.

## Table of Contents 

- Installation
- EDA Notebook
- ARIMA Notebook
- Facebook Prophet Notebook
- Data 

## Installation

Environment Variable saved in the file 'timeseries_vannia.txt'. This environment is the same like provided in class + 1 new package: pmdarima. In any problem with that package you can install pmdarima:

The safest procedure is with pip:

>>>pip install pmdarima

or 

>>>conda config --add channels conda-forge
>>>conda config --set channel_priority strict
>>>conda install pmdarima

### Activate environment
 
If the environment doesn't showed up at the kernel:

-In order to make run the packages in this environment, it is necessary to activate the environment
from the terminal:

>>>conda activate timeseries_vannia 

AND 

In Anaconda Navigator:

- 1 Click on the play icon of the environment timeseries_vannia
- 2 Single click and select running a jupyter notebook from the popped menu



---
## 01 EDA Notebook

This notebook contains Exploratory Analysis and contains the following index

- Descriptive Statistics
- System Representation
- Cleaning
- Tren Decomposition
- Stationarity
- Stationarity Preprocessing

#### There are internal links that connects the notebooks between each other

---
## 02 ARIMA Notebook

#### In case the verbosity returns a some warning, please restart the notebook and run it again, then it will work well.

Time series modeled through SARIMAX from statsmodel on different type of series:

- Differenced data
- Original data
- Grid Search with seasonal component
- Logaritmic transformed data
- Model Evaluations
---
## 03 Facebook Prophet Notebook

- Modeling
- Evaluation
---
## data directory

- electric_power_stats.csv ---> complete dataset
- can_50_08.csv --->decluttered dataset with only the variables of interest

---

## Thanks

To all Brainstation Education Team for all their help and patience:

- Boris
- Arad
- Beth
- Will

---
