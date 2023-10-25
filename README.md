# Netflix Shows Data Analysis Project

![netflix](https://static1.colliderimages.com/wordpress/wp-content/uploads/2020/11/netflix-most-popular-movies.jpg)

This project analyzes a dataset containing information about Netflix shows. The dataset includes details about the shows, such as titles, directors, cast, release year, and more. The project aims to explore and understand the dataset, perform data cleaning and feature engineering, visualize various aspects of the data, and build time series forecasting models. Below is a summary of the project.

## Project Overview

The project consists of the following key steps:

### Data Import and Initial Exploration

The project begins with the importation of essential libraries and loading the Netflix shows dataset. The dataset is examined to understand its structure, including the number of rows, columns, and data types. Additionally, a brief preview of the dataset is provided to get an initial sense of the data.

### Data Preprocessing

In this section, unnecessary columns are dropped, and the "date_added" column is converted into a timestamp format. Feature engineering is performed to create new columns for the added month, year, day, and day name. Visualizations are created to show the number of shows added each year and the ratio of movies to TV shows on Netflix.

### Top Categories and Countries

Two sections focus on the top categories and countries in the dataset. The top 10 categories of shows and the top 5 countries producing shows on Netflix are visualized to provide insights into popular content and geographical distribution.

### Time Series Analysis

The final part of the project delves into time series analysis. The dataset is aggregated to show the count of shows added over time. Rolling statistics and a Dickey-Fuller test are applied to check for stationarity. Transformation techniques are used to make the time series stationary.

### Modeling

Time series modeling is performed, including ARIMA and ARMA models. The selected model's summary is provided along with visualizations of the model's fit to the data.

## Conclusion

The project explores and analyzes a dataset of Netflix shows, from data preprocessing to time series modeling. It aims to provide insights into the dataset and demonstrate the process of data analysis and time series forecasting.

 
