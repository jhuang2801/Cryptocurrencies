# Cryptocurrencies

In this exercise, Cryptocurrency data collected from https://min-api.cryptocompare.com/data/all/coinlist is used to create classification system for a new investment. 

1. First the data was preprocessed by removing cryptocurrencies that are not being traded and any null values. Then a new dataframe is created to store all the information names and convert text strings to variables for machine reading. 

2. The new created dataframe is then reduced and fitted using PCA algorithm down to three principal components. 

3. Next, the PCA data is then clustered using K-mean algorithm. An elbow curve is created using hvplot to find the best value for K (which is 4).

4. Lastly, the results are visualzed using a 3-D scatter plot. A hvplot scatter plot is also created to demonstrate the relationship of "TotalCoinsMined" to "TotalCoinsSupply", using the "class" as the order.
