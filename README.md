# Cryptocurrencies


 ## Overview of Project
This project’s objective is to create a report that includes what cryptocurrencies are on the trading market and to group them to create a classification system. 
The deliverables for this project are:

*	Preprocess the data for Principal Component Analysis (PCA)
* 	Reduce Data Dimensions using PCA				
*	Cluster cryptocurrencies using K-means
*	Visualize cryptocurrencies results

## Software
Python, Pandas Jupyter notebook and Machine Learning. 

## Results 
### Preprocess the data for PCA.
In this stage of the data manipulation, inaccurate and unnecessary data was identified and removed from the dataset, null values were removed, a filter was applied, two columns were dropped (IsTrading and CoinName) and data was standardized with StandardScaler().


Before


![image](https://user-images.githubusercontent.com/86136535/139607404-08841536-6b93-4db3-a344-ed3b547c80ee.png)


After


![image](https://user-images.githubusercontent.com/86136535/139607417-d4a03629-504c-4156-84e3-dd7ab3bbd460.png)


### Reduce Data Dimensions using PCA.

A new dataframe was created and the dimensions of the X dataframe were reduced to three principal components.


![image](https://user-images.githubusercontent.com/86136535/139607438-2d7604d0-6e37-4063-af0c-813a36974db5.png)


### Cluster cryptocurrencies using K-means.
Using hvPlot an elbow curve was created to find the best value for K and predictions were made on the K clusters of the cryptocurrencies.



![image](https://user-images.githubusercontent.com/86136535/139607453-9a1372db-a73b-4e65-90d5-04c3714f1d41.png)


### Visualize cryptocurrencies results.
Using hvPlot a 3D visualization was created for the three principal components created.


![image](https://user-images.githubusercontent.com/86136535/139607465-7a69df36-75a2-41dd-a577-c71dc9b94ef2.png)


### Create a table using hvplot.table()
A table with tradable cryptocurrencies were created. 


![image](https://user-images.githubusercontent.com/86136535/139607477-4ea0268d-e8ee-46c0-bf17-31c9db4c97a0.png)


A Scatter plot using TotalCoinsMined and TotalCoinSupply was created.


![image](https://user-images.githubusercontent.com/86136535/139607489-744c3117-29c2-4b2d-8cdc-1954835cdb93.png)








