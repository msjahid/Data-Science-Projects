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
   - [Distribution of Content Types: Movies vs. TV Shows](#distribution-of-content-types-movies-vs-tv-shows)
   - [Release Year vs. Duration Scatter Plot](#release-year-vs-duration-scatter-plot)
   - [Count of Movie Genres](#count-of-movie-genres)
   - [Genre vs. Movie Duration Scatter Plot](#genre-vs-movie-duration-scatter-plot)
   - [Distribution of Movie Durations](#distribution-of-movie-durations)
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

![Data Distributions](music_charts/Missing%20Value%20Bar%20Graph.png)

### Distribution of Content Types: Movies vs. TV Shows

![Distribution of Content Types: Movies vs. TV Shows](movie_charts/Distribution%20of%20Content%20Types%3A%20Movies%20vs.%20TV%20Shows.png)

### Release Year vs. Duration Scatter Plot

![Release Year vs. Duration Scatter Plot](movie_charts/Release%20Year%20vs.%20Duration%20Scatter%20Plot.png)

### Count of Movie Genres

![Count of Movie Genres](movie_charts/Count%20of%20Movie%20Genres.png)

### Genre vs. Movie Duration Scatter Plot

![Genre vs. Movie Duration Scatter Plot](movie_charts/Genre%20vs.%20Movie%20Duration%20Scatter%20Plot.png)

### Distribution of Movie Durations

![Distribution of Movie Durations](movie_charts/Distribution%20of%20Movie%20Durations.png)

## Conclusion 🎉

In this project, I embarked on an exploratory analysis of Netflix TV series and movies, aiming to uncover insights into viewership patterns and trends over time. By examining a dataset containing various attributes such as ratings, duration, and release year, I gained valuable insights into the content landscape of Netflix.

Through my analysis, I discovered several key findings:

- Content Distribution:
  I observed a diverse range of content types on Netflix, including movies and TV shows. The distribution of content types provides valuable insights into the platform's content strategy and audience preferences.

- Genre Preferences:
  Analyzing the count of movie genres revealed popular genres among Netflix viewers. Understanding genre preferences can aid content creators and platform managers in curating a compelling content library.

- Temporal Trends:
  By visualizing the release year vs. duration scatter plot, I identified temporal trends in content production. These trends can inform decision-making regarding content acquisition and production strategies.

- Viewer Engagement:
  Exploring viewer engagement through scatter plots helped me understand the relationship between genre, duration, and viewer interest. These insights are crucial for optimizing content recommendations and enhancing viewer engagement.

Overall, my exploratory analysis provides valuable insights into the content landscape of Netflix and offers a foundation for further in-depth analysis and modeling. By leveraging data-driven insights, content creators, platform managers, and stakeholders can make informed decisions to enhance the Netflix viewing experience and drive business success.
