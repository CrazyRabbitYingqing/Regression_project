# Web Scraping and Regression Project Writeup
## Estimating Movie Revenue

### Abstract

The goal of this project was to use regression models and web scraping tools to predict the domestic gross revenue of a movie, in order to help a movie invester to get familiar with the movie market and make the right choice. I worked with data from the website: https://www.boxofficemojo.com/. I applied BeautifulSoup and Quest to scrape data from the website, including Movie Domestic gross, theater, MPAA... After performed basic data cleaning and visualization to the raw data, I conducted feature engineering on the categorical data. I used six regression models including: Simple Linear Regression, Simple Linear Regression with Cross-validation, Polynomial Regression, Lasso, Ridge, ElasticNet, to predict the movie gross revenue based on approximately 70 parameters. In the end, I selected 3 movies randomly as the potential investment choice, and then predict the movie gross revenue using the best fit model (Simple Linear Regression with Cross-validation).

### Design

This project can be separated into three parts:
1. Web scraping
2. Regression model and evaluation
3. Prediction

### Data

Data Source: https://www.boxofficemojo.com/

Data Time Period: 2010~2020

Raw Data Sice: ~2000 row, 13 cols

Cleaned and Featured Data: ~1100 row, ~70 cols

### Algorithms

*Feature Engineering

Converting categorical features to binary dummy variables.

Drop features that does not highly correlated.

*Models

Simple Linear Regression, Simple Linear Regression with Cross-validation, Polynomial Regression, Lasso, Ridge, ElasticNet.


### Tools

BeautifulSoup and Quest to scrap data

Numpy and Pandas for data manipulation

Scikit-learn for modeling

Matplotlib and Seaborn for plotting

scipy for stats plot

### Communication

The model evaluation, comparison, and performance will be presented in the Slides.
