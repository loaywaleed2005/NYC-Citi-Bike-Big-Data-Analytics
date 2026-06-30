# NYC Citi Bike – Big Data Analytics

A large-scale data engineering and analytics project that processes approximately 1.3 million NYC Citi Bike trips using Apache Spark and PySpark.

## Project Overview

This project demonstrates an end-to-end big data workflow including:

- Data loading and schema preparation
- Data cleaning and noise detection
- Feature engineering
- Spark-based aggregations
- Business-oriented analysis
- Interactive visualizations
- Machine learning using Spark ML

## Dataset

The dataset contains approximately 1.3 million Citi Bike trips with information about:

- Start and end times
- Start and end stations
- Station coordinates
- Bike IDs
- User type
- Rider birth year
- Gender

## Data Cleaning

The project identified and removed invalid records based on:

- Invalid rider ages
- Unrealistic trip speeds
- Invalid trip durations
- Missing essential identifiers

## Feature Engineering

The following features were created:

- Rider age
- Trip duration
- Trip distance
- Average trip speed
- Starting hour
- Period of day
- Season
- Weekday or weekend classification

## Machine Learning

The project compares:

- Logistic Regression
- Decision Tree
- Random Forest

## Technologies

- Python
- Apache Spark
- PySpark
- Spark SQL
- Spark ML
- Pandas
- Plotly
- Google Colab

## Project File

Open `NYC_Citi_Bike_Big_Data_Analytics.ipynb` to view the full project.

## Author

Loay Waleed
