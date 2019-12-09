# Data Science
There are some projects I have done at MIT as an exchange student. The original datasets are not available to the public. The purpose of this repo is to show my data science skills, such as importing and cleaning data, network analysis, time series analysis and data visualization. 

See the details in Jupyter Notebook by clicking links.

## 1. Single-cell RNA-seq analysis
* [Single-cell RNA-seq analysis](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Single-cell%20RNA-seq%20analysis.ipynb): Data dimension reduction and visualization


## 2. Ocean Flow Analysis
* [Flows and correlation](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Ocean_Flow/Ocean_Flow_1.ipynb): Finding the ocean flow and correlation patterns
* [Predicting trajectories](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Ocean_Flow/Ocean_Flow_2.ipynb): Simulating the trajectory of a particle moving in the flow
* [Path planning](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Ocean_Flow/Ocean_Flow_3.ipynb): The goal of this part is route a boat through the ocean water  with minimizing the travel time

## 3. Criminal Network Analysis
* [Investigating a time-varying criminal network](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Criminal_Network_Analysis/Criminal_Network_Analysis_1.ipynb): Investigating a time-varying criminal network that is repeatedly disturbed by police forces in CAVIAR project
* [Co-offending Network](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Criminal_Network_Analysis/Criminal_Network_Analysis_2.ipynb): Constructing and analyzing the co-offender network in Canada

## 4. Time Series Analysis
* [Consumer price index data analysis](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Time_Series/Time_Series_1.ipynb): The goal of this part is to analyze the PriceStats data from the MIT Billion Prices Project
* [The Mauna Loa CO2 concentration](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Time_Series/Time_Series_2.ipynb): The goal of this part is to fit the data with some time series models and understand its variations
      
## 5. Cryptocurrency Market Analysis Project
This is the MIT 6.419 (Statistics, Computation and Applications) subject final team project.

* [Project Report](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Cryptocurrency_Market_Analysis_Project/6.419_Project_Cryptocurrency_Market_Analysis.pdf)
* [Project Poster](https://nbviewer.jupyter.org/github/yuhaochen1997/Data-Science/blob/master/Cryptocurrency_Market_Analysis_Project/6.419_Project_Poster.pdf)

The cryptocurrency market is an interesting new part of the financial world, with the advent of blockchain technology showing great promise for the future of decentralized systems. However, the cryptocurrency market is not well understood, as people question the inherent value of cryptocur- rencies as well as the legitimacy of cryptocurrency exchanges (e.g. risk of market manipulation). In order to get a good understanding of how the cryptocurrency markets work, we attempt to answer the following questions:
1. What currencies serve as a good representation of the whole market?
2. How to quantify the goodness of such representation?
3. How we can predict the price movement efficiently?
4. How to detect when the market is stable and what are the consequences of it being unstable?
5. How is the behavior of the market on the hour horizon is different from its behavior on the week horizon?

In order to investigate the first two questions, we will employ network analysis that will show us how different currencies are related in terms of trade activity and correlation of their price movements. We also find network analysis to be beneficial, as it allows us to capture interdependencies and mutual positioning of the cryptocurrencies in the market (one of our trivial findings show that most currencies are exchanged via bitcoin). We proceed with analyzing time series with classical techniques and then move to an RNN model. Finally, we compare our findings on the macro scale with the intraday analysis, which attempts to look at trading activity on a smaller time scale.
      
