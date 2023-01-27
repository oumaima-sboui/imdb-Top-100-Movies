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
* year_of_release  
* category
* run_time 
* genre
* imdb_rating
* votes 
* gross_total

## Technologies and installation
### Technologies
Project is created with:
* An IDE, text editor or notebook environment
* Python 3.7 - Python 3.10

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


