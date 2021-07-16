# 365 TRADER AI


### A Machine Learning Trading Algorithm Project

Before you proceed, please read our disclosure at the bottom of this page.



   ![Bitcoin-Traders-–-The-Official-Trading-Bot](https://user-images.githubusercontent.com/80144026/125231211-2c844a00-e28f-11eb-9f95-b3c4a9ba0832.png)


## Presentation with Results and Analysis

[Click here to view our full presentation with the results and analysis](https://prezi.com/view/lmdvi3ffayMKfw1AQl3Q/)

## Executive Summary

* In this project we are building a cryptocurrency machine learning trading algorithm focusing on Bitcoin, and that can be used for any crytocurrency asset.
* Machine Learning is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention. In this project, Machine Learning will provide price forecasting, create trading signals, and identify correlation of crytocurrency assets.

     ![machine-learning-concept](https://user-images.githubusercontent.com/80144026/125231252-41f97400-e28f-11eb-8869-009c19b65870.jpg)


## Project Goals 

* Our audience are investors/traders who are looking for techniques to maximize their opportunities for success, establish preconditions to check on their portfolios and for buying/selling assets. They are also looking for other assets that are correlated, allocate these assets to diversify their crypto portfolio, and identify assets that may bring more returns percentage wise than the others, possibly making more profits at a more accelerated pace and prevent loss.

* In this project we are focused on Bitcoin because it is the largest cryptocurrency by market cap, and for its exceptional market growth. 

* We selected a few other assets which are called "altcoins" because Bitcoin and other coins tend to go through cycles. It may be the case that Bitcoin rallies for a period then stalls out. At this point, altcoins tend to take their turn rallying. This gives an opportunity for our traders to plan and execute profitable long and short trading strategies.

    ![Bitcoin-And-Ethereum-Lacking-Buy-Volume-Altcoins-Surges](https://user-images.githubusercontent.com/80144026/125237852-31e79180-e29b-11eb-9c6d-d02d1bb63bb3.png)





## Project Sections

* First, we used prophet by Facebook to predict future pricing for Bitcoin and the selected Altcoins from most recent data. Then we identified correlated assets.
* We wrote machine learning trading algorithms and ran three models to find the one that performed the best.
* Lastly, we explored an algorithm for long and short positions that uses DMAC Trading Strategy,and short positions. We backtested each trading strategy and evaluated the risk/reward metrics and then we evaluated the trade and portfolio.


## Machine Learning Models
* We used Supervised Learning > Classification: SVM, Logistic Regression, Naive Bayes

![Supervised-Learning](https://user-images.githubusercontent.com/80144026/125231479-acaaaf80-e28f-11eb-838f-d0a29a4dd597.jpg)


## Data Collection Source
* We used the most recent crypto currency data from [coindesk.com](coindesk.com) under [RESOURCES](https://github.com/talibkateeb/Crypto-Forecast-Trader/tree/main/data) 


## Technologies

This project is written in Python within the Jupyter Lab environment with the following packages:

* Pandas
* Numpy
* Scikit Learn
* Hvplot
* FBProphet


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


## Contributors

* [Talib Kateeb](https://github.com/talibkateeb)
* [Nestor Ramirez](https://github.com/nestor39)
* [Van Maquilan](https://github.com/VanMSM)

## Disclosure

The content contained in this project is for informational purposes only. You should not construe any such information or other material provided pursuant to the Course (the “Materials”) as investment, ﬁnancial, tax, legal or other advice. The Materials are not investment advice and any observations concerning any security, trading algorithm or investment strategy provided in this project is not a recommendation to buy, sell or hold such investment or security or to make any other investment decisions. The contributors do not provide any advice regarding the nature, potential value, risk or suitability of any particular investment strategy, trading algorithm, transaction, security or investment. Any use of the Materials, and any decisions made in reliance thereon, including any trading or investment decisions or strategies, are made at your own risk. You should seek the advice of a competent, licensed professional if you require investment, trading or other advice.The contributors do not provide any professional advice in connection with this project. Nothing contained in the Materials constitutes a solicitation, recommendation, endorsement, or offer by the contributors to buy or sell any securities or other ﬁnancial instruments in this or in in any other jurisdiction whether or not such solicitation or offer would be unlawful under the securities laws of such jurisdiction.


## License


[Click here to view MIT License](https://github.com/talibkateeb/Crypto-Forecast-Trader/blob/main/LICENSE)



