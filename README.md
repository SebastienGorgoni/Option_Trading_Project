# Option Trading Project
Option Trading Project for the Course Advanced Data Analytics - HEC Lausanne - Spring 2021

![alt text](https://camo.githubusercontent.com/c327657381291ed9f2e8866cb96ac4861431d9c244b7b14dcf4e1470cbf632da/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61332f4845435f4c617573616e6e655f6c6f676f2e7376672f32393370782d4845435f4c617573616e6e655f6c6f676f2e7376672e706e67)

## Data

* Download and clean option data
* Keep only stock with a large market cap
* Merge option data, with stock data --> we need to compare the option to the stock to measure returns
* Efficient data-loading (pickle)

## Portfolio class

* Cash invested
* Options held
* Trading decisions (buy sell)
* Free cash management

## Performance measure

* Returns
* Sharp-ratio
* Alphas <- factor regression and keep the alpha r = alpha + beta_1*mkt + beta_2 * mom + beta_3 HmL +...
* Trading strategies

## Define and pre-process/code some features/predictors

Use some ML model to make prediciton about stock --> trade on those signals 
a) signals about the mean direciton fo the stock, 
b) signals about specific part of the distributions of asset. 

Use ML to define an option-pricing model which is going to price the whole cross section and we buy whatever the algorithm deems underated.
