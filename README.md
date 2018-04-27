##Retail sale predicitons with multiple algorithms  

-------------------------------------------------------------------------------------------------------------------------------
Today, online shopping is growing really fast. Our project is about the online store income forecast, Real retail shop sale prediction based on random forest model, and BigMart retail sale prediction.
To make a research of retail business by the data science technology, the whole project is divided into three parts:In the first part, we cleaned and explored data first. Then we used RNN/LSTM to forecast the online store daily income. The second part, different csv files were merged and the prediction was made by Random Forest Model. The third part, we used five models try to understand the properties of products and stores, and to find out which part plays a key role in increasing sales.

Part 1(RNN,LSTM):
-----------------------------------------------------------------------------------------------------------------------------------------
In the first part of our project, we use the python method in data cleaning and data explore. And we can use graph find some features in the dataset which can let us know the pinpoint of this dataset. And then, we decide to use RNN/LSTM on forecast the store daily income. So we use python to calculate daily income and make this dataframe transfer to a time-series dataframe. Finally, we had a forecast result for daily income.

part 2(Random Forest):
----------------------------------------------------------------------------------------------------------------------------------------
Similarly in real retail part of code we start with data clean.Besides,forecasts were based simply on a median of the weekly sales grouped by the Type of Store, Store & Department number, Month and Holiday dummy and ,correlation map do helps us to measure which features is really useful and which makes little contribution to the final prediction. What’s more,The input csv file is merged by 5 datasets that makes the pre-progress very hard.


part 3(KNN,Multinomial Classifier and OneVsOneClassifier):
----------------------------------------------------------------------------------------------------------------------------------------
In the third part of our project, there are two datasets used. The first is “train”, the second is “test”. The “test” was used to test whether we had found the good prediction and got the good understanding of the data. We used some methods to clean the dataset we got first, then for a better use of the dataset, we put a new column “Quantity Sold”, as quantity of sold is a good standard to test which factor influenced the sales most. After that, we built a classifier changing the categorical data to numeric/dummy. Then we used the algorithms of K-Nearest Neighbours to get the value of accuracy. Besides, we used five models Decision tree Regression, Ridge, Adaptive Boost, LASSO,Random Forest to get five predictions, and then compare these five different results.



