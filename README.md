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


## Results and Analysis 

[Click here to view our full presentation with the results and analysis](https://prezi.com/view/lmdvi3ffayMKfw1AQl3Q/)

  # Based on Facebook Prophet forecasts for each coin, it appears that all the coins will have an upward trend in the near future.

<img width="849" alt="Screen Shot 2021-07-16 at 1 55 39 AM" src="https://user-images.githubusercontent.com/80144026/125922443-e1ea8394-979b-4ac5-8f9b-5328de48cb69.png">

<img width="829" alt="Screen Shot 2021-07-16 at 1 55 51 AM" src="https://user-images.githubusercontent.com/80144026/125922467-ac041708-9fe1-4b00-85e5-4921b7c2ec88.png">

<img width="832" alt="Screen Shot 2021-07-16 at 1 55 58 AM" src="https://user-images.githubusercontent.com/80144026/125922482-14f90f35-bc26-49b7-8283-44c418b639d3.png">

<img width="798" alt="Screen Shot 2021-07-16 at 1 56 06 AM" src="https://user-images.githubusercontent.com/80144026/125922494-566faefb-5c0f-4c60-b9ca-67592ea3462f.png">


# If we also examine the forecast trends for the lower and upper values for y-hat, we see that the upward trend holds true in the forecasts for all coins.

<img width="849" alt="Screen Shot 2021-07-16 at 1 56 12 AM" src="https://user-images.githubusercontent.com/80144026/125922557-c33dfa8c-392e-4d4b-a931-9a45d91691db.png">

<img width="838" alt="Screen Shot 2021-07-16 at 1 56 18 AM" src="https://user-images.githubusercontent.com/80144026/125922671-b5e7f6dc-27fb-45f3-9a6d-435e97fdee5c.png">

<img width="1172" alt="Screen Shot 2021-07-16 at 1 59 32 AM" src="https://user-images.githubusercontent.com/80144026/125922705-05cb5c2a-ceec-4cbe-b4ec-6581d0c4be0f.png">

<img width="1204" alt="Screen Shot 2021-07-16 at 1 59 41 AM" src="https://user-images.githubusercontent.com/80144026/125922728-911697f3-ad9d-46b4-a16c-6be249b27a25.png">


# Price of Bitcoin peaks usually on Wednesday. Price of Bitcoin peaks usually around March/April.

<img width="849" alt="Screen Shot 2021-07-16 at 1 59 49 AM" src="https://user-images.githubusercontent.com/80144026/125922783-e5bace66-e1d9-46b7-853c-9c0af2cf034e.png">


# Based on the calculated correlation, we can see that Litecoin correlates the most closely with Bitcoin, then Ethereum, then Cardano. 

<img width="849" alt="Screen Shot 2021-07-16 at 1 59 55 AM" src="https://user-images.githubusercontent.com/80144026/125922813-2357f12e-bc5b-4678-956f-dbd6dc96481c.png">


# We then evaluated the three different models using a classification report. Based on the evaluations, the logistic regression classification model performed the best. 

<img width="849" alt="Screen Shot 2021-07-16 at 2 00 08 AM" src="https://user-images.githubusercontent.com/80144026/125922842-4bffd431-edda-4a0e-a0f7-9d1681252447.png">

<img width="849" alt="Screen Shot 2021-07-16 at 2 00 16 AM" src="https://user-images.githubusercontent.com/80144026/125922879-38c3f203-c707-4bad-8579-af1da6ef3337.png">

<img width="849" alt="Screen Shot 2021-07-16 at 2 00 23 AM" src="https://user-images.githubusercontent.com/80144026/125922911-a69cc734-2dbb-4298-8c0c-16177a0a0b55.png">


# Overall, it seems that our DMAC Long Position Trading Algorithm produces minimal loss and impressive returns on investment.

<img width="849" alt="Screen Shot 2021-07-16 at 2 07 21 AM" src="https://user-images.githubusercontent.com/80144026/125923262-561d9e44-d3c4-437a-b67e-3be801e91790.png">

<img width="1287" alt="Screen Shot 2021-07-16 at 2 07 37 AM" src="https://user-images.githubusercontent.com/80144026/125923283-a1cf2651-4640-4762-87fa-ae27cc5c0b14.png">


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



