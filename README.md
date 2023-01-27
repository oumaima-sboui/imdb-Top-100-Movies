# imdb-Top-100-Movies-interactive-dashbord

## Table of contents
* [About the project](#About the project)
* [About dataset](#About dataset)
* [Technologies and installation](#Technologies and installation)
* [Result](#steps)



## About the project
This repo contains code for the portfolio project which aims to create and visualize an interactive  dashboard for IMDb Top 100 Movies dataset in Python.

## About dataset
IMDb Top 100 is the list  of highest rated movies of all time  according to IMDb platform ,this dataset is taken from [kaggle's datasets](https://www.kaggle.com/datasets/themrityunjaypathak/imdb-top-100-movies)
Movie in the list ranges from 1972 to 2015.
There are 100 Rows and 9 Columns in the Dataset :
* movie_name 
*year_of_release  
*category
*run_time 
*genre
*imdb_rating
*votes 
*gross_total

## Technologies and installation
### Technologies
Project is created with:
*An IDE, text editor or notebook environment
*Python 3.7 - Python 3.10

### installation
apart the basic libraries you have to install 
*[panel](https://panel.holoviz.org/index.html) : an open-source Python library that lets you create custom interactive web apps and dashboards
*[hvplot](https://hvplot.holoviz.org/index.html) :  a powerful and interactive Pandas-like .plot() API
You can use either conda or pip. In this project i provide the instructions/commands for pip:
**Panel**
```
pip install panel
```
**Hvplot**
```
pip install hvplot
```
To serve the dashboard locally, use the command:
```
pip install panel hvplot pandas scipy matplotlib jupyterlab
jupyter serverextension enable panel.io.jupyter_server_extension
panel serve ise.ipnyb
```

## Result
### EDA(expaporatory data analysis) : [click here to view the code](https://github.com/oumaima-sboui/analysis-and-clustering-of-data-world-university-ranking/blob/master/DATA_VIZ%26ANALYSIS.ipynb) 
 the data , we use , is the World University Ranking which aims to investigate the best universities in the world and since we are dealing with many variables at the same time ==>  we are processing a  <b>multivariate exploratory analysis</b>.   
When doing any data analysis it is important to understand first as much about the meaning of the data as possible.For that, we start by 
* undrestand  the data
* prepare the data
* cleaning and pretraitement of data (dealing with missing values, ...)
* show the features, the correlation between them, in differents diagrams ,tables, plots
* extracts insights 

### Perform clustring algorithms : [click here to view the code](https://github.com/oumaima-sboui/analysis-and-clustering-of-data-world-university-ranking/blob/master/Data_clustering_university_rank.ipynb) 

Clustering is an unsupervised learning method which groupe unlabeled examples.
it's the task of dividing the population or data points into a number of groups such that data points in the same groups are more similar to other data points in the same group and dissimilar to the data points in other groups. It is basically a collection of objects on the basis of similarity and dissimilarity between them.[(For more click here)](https://www.geeksforgeeks.org/clustering-in-machine-learning/).
We follow the steps below :
* carry out 4 approaches of clustering : k-means , Affinity Propagation , DBSCAN and hierarchical clustering.
* evaluate them by the measurement of metrics.

