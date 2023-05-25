# **UCB FinTech Bootcamp Module 10 Challenge**
# *Crypto currency Investment Portfolio*
## **Introduction**
### The Bootcamp Module 10 Challenge - Cyrpto Currency Investment Portfolio assumes the preparation of a portfoio composed of crypto currency tokens, analyzing the trends in the price changes for different periods: daily (24 hrs), weekly (7 days), bi-weekly( 14 days), monthly (30 days), bi-monthly (60 days), semi-annually (200 days) and annually (1 year). 
---
## **Goals and Objectives**
### *Part I.*  Using the original data, find the optimal number of clusters (k) for grouping and analyzing the 41 crypto currencies listed in the data set using the 'Elbow method'
### *Part II.*  Group the crypto currencies in the 'k' number of clusters defined and create a graph to visually analyze the grouping (e.g. are there overlaps, are the groups clearly defined/delineated)  
### *Part III.*  Optimize the clustering using the Principal Component Analysis (PCA) method finding the best 'k' number of clusters for the reduced number of features, again using the 'Elbow method' for the PCA data set.
### *Part IV.*  Group the crypto currencies in the PCA-based 'k' number of clusters and create a graph to visually analyze this new PCA-based grouping (e.g. are there overlaps, are the groups clearly defined/delineated) 
### *Part V.*  Compare the Elbow method results - using the origninal data vs. using the PCA method - by contrasting the graphs from each analysis and further, compare the clustering results of the initial data vs. the PCA-based clustering by comparing the corresponding graphs for each method and the proposed grouping (which method provides clearer, better defined/delineated groups/clusters) 
---
## **Technologies and Tools**
### The following list includes the main technologies and tools using during the preparation and deployment of the solution:
### 1. *Python* - Programming language used to code the solution. Version 3.7.13 was used. Required libraries and frames listed in the Installation section below
### 2. *GitHub* - Reposotory for code deployment, version management and documentation of the presented solution
### 3. *Jupyter Labs* - IDE tool for coding, code testing/debugging and solution documentation. Version V3.4.4 was used
### 4. *Git Bash console* - Local console used to test the coded solution and sync wiht GitHub Version 2.40.0.windows.1 was utilized
### 5. *Slack* - Collaboration tool to communicate and brainstorm with other FinTech Bootcamp participants
### 6. *Operative System* - This solution was prepared in a PC running Windows 11 v H22
### For additional details, please refer to the watermark output at the bottom of the Jupyter Notebook
---
## **Installation Guide**

### 1. [Pandas](https://pandas.pydata.org/) : Pandas is a powerful and widely used open-source Python library for data manipulation and analysis. It provides data structures and functions that make working with structured data, such as tabular data, more efficient and convenient. Just in case, if you have to install, the instructionsa are:
#### 3.1. Open the GitBash terminal
#### 3.2 Type the following command and press Enter:
```python 
pip install pandas
```
### 2. [Plotly](https://plotly.com/) : Plotly is an open-source Python library that allows you to create interactive and visually appealing data visualizations. It provides a high-level interface for creating a wide range of charts, including line plots, scatter plots, bar plots, pie charts, 3D plots, maps, and more. Plotly supports both offline and online plotting, making it suitable for various use cases. Install in your environment following the steps below:
#### 2.1. Open the GitBash terminal
#### 2.2 Type the following command and press Enter:
```python 
pip install plotly
```
### 3. [hvplot](https://hvplot.holoviz.org/) : hvplot is a Python library that provides a high-level interface for creating interactive and visually appealing visualizations. It is built on top of HoloViews and provides a simplified API for generating plots directly from Pandas DataFrames, GeoPandas DataFrames, xarray datasets, and other data structures commonly used in the PyData ecosystem. To install, follow these steps:
#### 3.1. Open the GitBash terminal
#### 3.2 Type the following command and press Enter:
```python 
pip install hvplot
```
### 4. [sklearn](https://scikit-learn.org/) : scikit-learn, also known as sklearn, is a popular open-source machine learning library for Python. It provides a wide range of machine learning algorithms, tools, and utilities for tasks such as classification, regression, clustering, dimensionality reduction, model selection, and preprocessing of data. To install, follow these steps:
#### 3.1. Open the GitBash terminal
#### 3.2 Type the following command and press Enter:
```python 
pip install scitkit-learn
```
---
## **Solution Structure**

### The **[10.Crypto Portfolio](https://github.com/LUTOV001/10.Crypto_Portfolio)** repository in GitHub contains the solution components. The repository consists of the following folders, subfolders and contents as described below:
 
###   1. Resource : Includes the .csv files containing the crypto token price data in which the analysis is based. 
###   2. gitignore : Instructions for which files/file types to exclude from the sync process between GitHub and the local environment.
###   3. README.md : The present file containing this outline of the challenge and its components.
###   4. *crypto_investments.ipynb* : This is the Jupyter Notebook with the code for the core challenge solution.
###    
---
## **User Instructions**
### 1. Launch the Jupyter Lab from the GitBash terminal using the following command line:
```python 
jupyter lab
```
### 2.From the Jupyter Lab terminal, navigate to where the ***crypto_investments.ipynb*** notebook is located and open it
### 3.Reset the Kernel and
### 4.Run the steps in sequence and verify the results as per the comments in the notebook, including outputs on the screen such as dataframe listing/on screen pring and generated graphs/plots (e.g. plot images for the Elbow and Clustering results)
####
---
## **Credits**

### Prepared by Luis Torres 
### [LUTOV001](https://github.com/LUTOV001)
### May 2023
