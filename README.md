# Transformer-for-Stock-Price-Prediction and Golden-Cross Strategy
- ZHANG MIAN
- CentraleSupélec

This file is a brief introduction about Transformer Model and the application in finance domain.

### What we have got

The prediction of the Moving Average (10days)

![image](https://user-images.githubusercontent.com/110284601/186769095-4b65b504-04f3-4480-bd0e-3f56d1f21df9.png)

The loss function with the epochs.

![image](https://user-images.githubusercontent.com/110284601/186769133-cba6633e-7172-4375-8ab5-a768ece35b8a.png)



## 1. Introduction to Transformer Model
The fundamental thesis of Transformer Model: <Attention is all you need> 
Link: https://arxiv.org/pdf/1706.03762.pdf
  
## 2. Import and labs and preprocess the data
  In this project we calculate the percentage return of the daily stock price(Open, Close, High, Low, Volume)
  
## 3. Construct Transformer model by Tensorflow.
  - Time Embedding 
  - Single Head Attention 
  - Multi Head Attention 
## 4. Moving Average Case and Golden-Cross Strategy
  Here we define the moving average of 20 trading days, all rest the same. And also we recalculate the 60 days moving average. 
  If the golden-cross shows up, we decide to buy the stock(Also this should be conducted with RSI or other index).
  
