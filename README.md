# cryptocurrencies

## Overview
Create an analysis for clients that are preparing to get into the cryptocurrency market and produce a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for a new investment.

## Results
After generating an elbow curve, we can see that the optimal number of clusters are 4 (k=4).

<img width="619" alt="elbow" src="https://user-images.githubusercontent.com/83614893/168446328-83c40e59-945d-4887-8319-46c227561ba5.png">

> Figure 1. Elbow Curve

with this information a 3D plot is generated as follows: 
![3Dplot](https://user-images.githubusercontent.com/83614893/168446346-8ab3493c-d6a4-4b95-af2e-91bd276ef906.png)
> Figure 2. 3D plot 

we can see the 4 different clusters that are generated.

A hvTable is generated displaying all of the currently tradeable cryptopcurrencies according to our dataset.

<img width="602" alt="hvTable" src="https://user-images.githubusercontent.com/83614893/168446439-59ed2fd0-4f26-48b6-9699-db8b63b8aa6d.png">

> Figure 3. hvTable 

with this information we obtain a scatter plot grouped by class:
<img width="610" alt="hvPlot" src="https://user-images.githubusercontent.com/83614893/168446532-0bb6ab1a-0952-4ce9-96f8-2c2dee901340.png">
> Figure 4. hvPlot
