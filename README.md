
# 365 TRADER AI



   <img width="1003" alt="Screen Shot 2021-07-16 at 8 58 57 AM" src="https://user-images.githubusercontent.com/80144026/125976082-d78a39f7-7b88-4b09-a60f-030a92a48d87.png">



Before you proceed, please read our disclosure at the bottom of this page.

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
* Lastly, we explored an algorithm for long and short positions that uses DMAC Trading Strategy. We backtested each trading strategy and evaluated the risk/reward metrics and then we evaluated the trade and portfolio.


## Machine Learning Models

We used Supervised Learning > Classification: SVM, Logistic Regression, Naive Bayes

![Supervised-Learning](https://user-images.githubusercontent.com/80144026/125231479-acaaaf80-e28f-11eb-838f-d0a29a4dd597.jpg)


## Data Collection Source

We used the most recent crypto currency data from [coindesk.com](coindesk.com) under [RESOURCES](https://github.com/talibkateeb/Crypto-Forecast-Trader/tree/main/data) 


## Results and Analysis 

<img width="1202" alt="Screen Shot 2021-07-16 at 3 25 43 AM" src="https://user-images.githubusercontent.com/80144026/125934503-0f7f906c-11ef-47e9-9938-e2c8c94f30e3.png">



[Click here to view our full presentation with the results and analysis](https://prezi.com/view/lmdvi3ffayMKfw1AQl3Q/)


### Based on Facebook Prophet forecasts for each coin, it appears that all the coins will have an upward trend in the near future.


<img width="700" alt="Screen Shot 2021-07-16 at 2 19 05 AM" src="https://user-images.githubusercontent.com/80144026/125925048-a8da839c-5a90-4062-ac90-9b0f236e83ec.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 55 51 AM" src="https://user-images.githubusercontent.com/80144026/125925063-abdf4682-48c6-4752-aad7-fbf84f696d9e.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 55 58 AM" src="https://user-images.githubusercontent.com/80144026/125925157-a538528a-a195-4a87-9a72-f0a4d2af7167.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 56 06 AM" src="https://user-images.githubusercontent.com/80144026/125925176-9942237d-e9f7-4a6c-945b-2e29b03d9568.png">



### If we also examine the forecast trends for the lower and upper values for y-hat, we see that the upward trend holds true in the forecasts for all coins.


<img width="700" alt="Screen Shot 2021-07-16 at 1 56 12 AM" src="https://user-images.githubusercontent.com/80144026/125925244-72a7b96b-f915-4bc5-962d-b08d77dfa57f.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 56 18 AM" src="https://user-images.githubusercontent.com/80144026/125925265-bed0a202-0d36-4103-8b6a-c896df2db197.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 59 41 AM" src="https://user-images.githubusercontent.com/80144026/125925328-de41afcd-912e-451c-b29a-124d475d87eb.png">

<img width="700" alt="Screen Shot 2021-07-16 at 1 59 41 AM" src="https://user-images.githubusercontent.com/80144026/125926126-0ae66e18-e738-4370-9503-b59809aded3c.png">



### Price of Bitcoin peaks usually on Wednesday. Price of Bitcoin peaks usually around March/April.

<img width="700" alt="Screen Shot 2021-07-16 at 1 59 49 AM" src="https://user-images.githubusercontent.com/80144026/125925402-e05f7ddd-72de-478a-9f84-b17d921c2d59.png">



### Based on the calculated correlation, we can see that Litecoin correlates the most closely with Bitcoin, then Ethereum, then Cardano. 

<img width="700" alt="Screen Shot 2021-07-16 at 1 59 55 AM" src="https://user-images.githubusercontent.com/80144026/125925549-0b0986fd-fc15-489e-bc08-17391ffa8edf.png">



### We then evaluated the three different models using a classification report. Based on the evaluations, the logistic regression classification model performed the best. 

<img width="700" alt="Screen Shot 2021-07-16 at 2 00 08 AM" src="https://user-images.githubusercontent.com/80144026/125925573-c04dd1b9-45c5-492d-ab7b-8b2e56cfcd16.png">

<img width="700" alt="Screen Shot 2021-07-16 at 2 00 16 AM" src="https://user-images.githubusercontent.com/80144026/125925615-04eab1b3-308b-4772-a56f-0994cfe8dbec.png">

<img width="700" alt="Screen Shot 2021-07-16 at 2 00 23 AM" src="https://user-images.githubusercontent.com/80144026/125925911-4fcf782b-a112-4cde-ad8d-0db7954fe071.png">



### Overall, it seems that our DMAC Long Position Trading Algorithm produces minimal loss and impressive returns on investment.



<img width="700" alt="Screen Shot 2021-07-16 at 2 07 21 AM" src="https://user-images.githubusercontent.com/80144026/125923262-561d9e44-d3c4-437a-b67e-3be801e91790.png">

<img width="700" alt="Screen Shot 2021-07-16 at 2 07 37 AM" src="https://user-images.githubusercontent.com/80144026/125923283-a1cf2651-4640-4762-87fa-ae27cc5c0b14.png">





## Conclusion

Based on the machine learning trading algorithm that we used, we found that,when used by itself, it is not a reliable tool for guaranteed profitability. But if used with other trading tools and methodologies like RSI, Bollinger Bands, MonteCarlo Forecasting and others, it can result in a profitable trade for predicting trade signals and strategy returns for both long and short positions.

## Next Steps

* Tune the hyper-parameters of the machine learning models with GridSearchCV. Major parameters include: Kernels, C (Regularisation), and Gamma.

* Explore more trading tools &  methodologies (Bollinger Bands, Monte Carlo Forecasting, RSI,  Gann Fann , Fibonacci retracement , etc.)

* Add a CLI using AWS Services to create a trader that users can interact with to give recommendations on trades.


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



