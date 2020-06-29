# Movie Recommendation Web App
![](Images/movie.jpeg)
# Overview

This is a content based movie recommendation web application hosted on Heroku. Just enter one movie name then it will recommend 25 movies.

# Demo
Link: https://nikmoviemaniac.herokuapp.com/

![](Images/demo.png)

# Dataset used
I have used TMDB 5000 movie dataset.              
This dataset containd two csv files:
  1. tmdb_5000_credits.csv
  2. tmdb_5000_movies.csv

Link to dataset: https://www.kaggle.com/tmdb/tmdb-movie-metadata

# Project lifecycle
* Cleaned the dataset
  * Dropped unimportant columns
  * Decoded JSON formatted columns
  * Removed numbers and special characters
  * Removed stopwords
  * Extracted imoportant phrases
  * Combined all columns except movies name
* Creating Flask app
* Deployment of the application on Heroku

# Libraries used
* Pandas
* Numpy
* Matplotlib
* Json
* Rake_nltk
* Regular expression
* Sklearn
* Flask

# Some important algorithms used
* [RAKE (Rapid Automatic Keyword Extraction)](https://pypi.org/project/rake-nltk/):
  
  This algorithm is used to extract important phrases from the body of the text.
* Nearest Neighbours:
  
  I have used nearest neighbours algorithm to find the most related list of movies to a movie name. This algorithm takes argument named **'metric'**.I have assigned this argument to **'cosine'**. If two movies are highly related then the cos value will be equal to 1 as angle between them will be 0 degree. If movies are not related then angle between them will be 90 degree and value will equal to 0 (cos90=0).
   
  
![](Images/cosine.png)

# Directory tree
![](Images/directory.png)

# Tool used
![](Images/jupyter.png)  ![](Images/spyder.jpg)

# Language used
![](Images/python.jpeg)

# Technologies used
![](Images/flask.png) ![](Images/gunicorn.png) ![](Images/heroku.png)

# Visit blog
[Click Here](https://medium.com/@NIKsaurabh/movie-recommender-web-app-e6c5ea5c4659)
