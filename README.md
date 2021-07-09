# CRYPTO FORECAST TRADER

A Machine Learning Trading Algorithm Project

## Executive Summary

* In this project we are building a cryptocurrency machine learning trading algorithm project focusing on Bitcoin, and that can be used for any crytocurrency asset.
* Machine Learning is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention. In this project, Machine Learning will provide price forecasting, create trading signals, and identify correlation of crytocurrency assets.
--

## Project Goals 
* Our audience are traders who are looking for techniques to maximize their opportunities for success, establish preconditions to check on their portfolios and for buying/selling assets. They are also looking for other assets that are correlated, and may bring more returns percentage wise than the others, allowing them to  execute trades at a much higher rate, possibly making more profits at a more accelerated pace.
* In this project we are focused on Bitcoin because it is the largest cryptocurrency by market cap, and for its exceptional market growth. 
* We selected a few other assets which are called "altcoins" because Bitcoin and other coins tend to go through cycles. It may be the case that Bitcoin rallies for a period then stalls out. At this point, altcoins tend to take their turn rallying. This gives an opportunity for our traders to plan and execute long and short trading strategies, and be profitable even when Bitcoin prices fall or rises. 
* We used prophet by Facebook to predict future pricing for Bitcoin and the selected Altcoins from most recent data.
* Lastly, our machine learning trading algorithm will create entry and exit signals and returns.
__

## Machine Learning Models
* We used Supervised Learning, Classification: SVM, Logistic Regression, Naive Bayes
__

## Results and Conclusions of the Machine Learning Model
(Under Construction)
__

## Data Collection Source
* We used the most recent crypto currency data from [Investing.com](https://www.investing.com/crypto/)
* Pull more cryptocurrency data that you want to analyze, add to the [RESOURCES](https://github.com/talibkateeb/Crypto-Forecast-Trader/tree/main/data) 

__

## Technologies

This project is written in Python within the Jupyter Lab environment with the following packages:

* Pandas
* Numpy
* Scikit Learn
* Hvplot
* FBProphet

__

## Installation Guide
Before running the application first install and verify the following dependencies:

* Pandas from PyPI
```python
pip install pandas
```
* Numpy from PyPI
```python
pip install numpy
```
* Scikit Learn from PYPI
```python
pip install -U scikit-learn
```
* HVPLOT using Conda. Best practice, use an environment rather than install in the base env
 ```python
 conda activate dev 
 conda install -c pyviz hvplot 
```
* FBProphet using Conda. The easiest way to install is through Conda. Best practice, use an environment rather than install in the base env
 ```python
 conda activate dev 
 conda install -c conda-forge prophet
```

Next, Import the Modules

 ```python
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report
from fbprophet import Prophet
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
```
Clone to your local repo and run in JupyterLab
__

## Next Steps
(Under Construction)

## Contributors

* [Talib Kateeb](https://github.com/talibkateeb)
* [Nestor Ramirez](https://github.com/nestor39)
* [Van Maquilan](https://github.com/VanMSM)
__


## License

Feel free to add to this code to improve it and use for your own project.


