# Exploratory Analysis of Netflix movie 🎬🌈🎞️

## Overview 📊

This project delves into the realm of music data analysis, focusing on exploring trends, patterns, and insights hidden within a comprehensive dataset. By leveraging Python and visualization techniques, we aim to unravel the intricate dynamics of the music industry, shedding light on factors such as artist popularity, track performance, and consumer preferences.

## Table of Contents 📑

1. [Introduction](#introduction)
2. [Dataset Exploration](#dataset-exploration)
   - [Data Overview](#data-overview)
   - [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Correlation Heatmap (Numeric Columns Only)](#correlation_heatmap)
   - [Sales, Streams, Downloads, Radio Plays Over the Year](#sales_streams_downloads_radio_plays)
   - [Top Ten Artists Based on Sales and Rating](#top_ten_artists_based_on_sales_and_rating)
   - [Histogram of Ratings](#histogram_of_Ratings)
   - [Relationship between Sales, Downloads, and Radio Plays over Time](#relationship_between_sales_downloads_and_radio_plays_over_time)
4. [Conclusion](#conclusion)

## Introduction 🚀

Understanding the dynamics of music sales is crucial for artists, producers, and industry stakeholders. In this project, we utilize data analysis techniques to uncover trends and patterns in music sales across different genres, time periods, and platforms. By examining factors such as artist popularity, release dates, and sales figures, we aim to provide insights into the music industry and help inform strategic decisions.

## Dataset Exploration 📊

### Data Overview

The dataset comprises information about Netflix content, including attributes such as show type, title, director, cast, country, release year, rating, duration, and genre. Exploring and preprocessing this data is the initial step in deriving insights and building effective analysis and recommendation models.

- Data Size: The dataset comprises 4850 rows and 8 columns, offering a substantial amount of information for analysis.
- Data Types: The dataset features a mix of data types, including int64, float64 and object.
- Missing Values: No missing values simplify data cleaning.
- Unique Values: The dataset contains 0 duplicate values, indicating that each row represents distinct information, eliminating redundancy.
- Irrelevant Features: While most features appear relevant, "title" is potentially irrelevant for analysis and could be excluded from further evaluation.

### Data Preprocessing

- In the data preprocessing phase, we first examined the shape of the data to understand its dimensions.
- Next, we checked for null values in the dataset and removed them if any were found.
- Additionally, we performed a check for duplicate values and replaced them to ensure data integrity.
- To gain insights into the relationships between different variables, we visualized the correlation map using a heatmap. This visualization allowed us to identify patterns and dependencies among the features in the dataset, helping us understand the interplay between various attributes.

## Exploratory Data Analysis (EDA) 📈

Exploratory Data Analysis involves visualizing and interpreting the dataset to extract meaningful insights. Let's explore some key aspects:

### Correlation Heatmap (Numeric Columns Only)

![Correlation Heatmap (Numeric Columns Only)](<music_charts/Correlation%20Heatmap%20(Numeric%20Columns%20Only).png>)

### Relationship Between Sales, Downloads, and Radio Plays over Time

![Sales, Streams, Downloads, Radio Plays Over the Year](music_charts/Sales%2C%20Streams%2C%20Downloads%2C%20Radio%20Plays.png)

### Top Ten Artists Based on Sales and Rating

![Top Ten Artists Based on Sales and Rating](music_charts/Top%20ten%20artists%20based%20on%20sales%20and%20rating.png)

### Histogram of Ratings]

![Histogram of Ratings](music_charts/Histogram%20of%20Ratings.png)

### Relationship between Sales, Downloads, and Radio Plays over Time

![Relationship between Sales, Downloads, and Radio Plays over Time](music_charts/Relationship%20between%20Sales%2C%20Downloads%2C%20and%20Radio%20Plays%20over%20Time.png)

## Conclusion 🎉

In this project, I embarked on an exploratory analysis of music sales, aiming to uncover insights into sales patterns and trends over time. By examining a dataset containing various attributes such as artist, title, year, sales, streams, downloads, radio plays, and ratings, I gained valuable insights into the dynamics of the music industry.

Through my analysis, I discovered several key findings:

- Sales Distribution:
  I observed a diverse range of music sales figures, highlighting popular tracks and their commercial success. This distribution provides valuable insights into the factors contributing to high sales volumes and overall market performance.

- Artist Popularity:
  Analyzing sales data by artist revealed trends in popularity and market impact. Understanding which artists consistently perform well can aid record labels and marketers in promoting similar artists and genres.

- Temporal Trends:
  By visualizing sales data over time, I identified trends in music consumption and production. These temporal trends can inform decision-making regarding release strategies and marketing campaigns.

- Engagement Metrics:
  Exploring engagement metrics such as streams, downloads, and radio plays helped me understand the relationship between different forms of consumption and overall popularity. These insights are crucial for optimizing distribution strategies and enhancing audience reach.

Overall, my exploratory analysis provides valuable insights into the music sales landscape and offers a foundation for further in-depth analysis and modeling. By leveraging data-driven insights, artists, producers, and industry stakeholders can make informed decisions to enhance music promotion and drive business success.
