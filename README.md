# Cryptocurrencies: Module 18 Challenge

## Overview of Project

### Background and Purpose

You and your childhood best friend Martha always dreamed of changing the world. When she gets the chance to pitch an investment in cryptocurrencies to her firm, Accountability Accounting, you jump at the chance to help out. After all, you both think that changing the world is what cryptocurrency is all about. Martha has a dataset of cryptocurrencies and can analyze it in any way she wants. It's your job to help Martha discover trends that will convince her firm to invest in these new currencies. You will need to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

### Resources

- Data Sources: crypto_data.csv (retrieved from https://min-api.cryptocompare.com/data/all/coinlist)
- Software: Anaconda 4.13, Jupyter Notebook, Python 3.7.13, Visual Studio Code 1.68.1

## Procedure

### Deliverable 1

Using your knowledge of Pandas, you’ll preprocess the dataset in order to perform PCA in Deliverable 2.

### Deliverable 2

Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

### Deliverable 3

Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

### Deliverable 4

Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.
