# Exploratory Analysis of Netflix movie 🎬🌈🎞️

## Overview 📊

This project delves into an exploratory analysis of Netflix TV series and movies, focusing on aspects such as ratings, duration, and yearly trends. By scrutinizing a dataset encompassing diverse attributes, including viewer ratings and time durations, our aim is to uncover insights into viewership patterns and trends over time.

## Table of Contents 📑

1. [Introduction](#introduction)
2. [Dataset Exploration](#dataset-exploration)
    - [Data Overview](#data-overview)
    - [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Missing Value Bar Graph](#missing_value_bar_graph)
    - [Distribution of Content Types: Movies vs. TV Shows](#distribution-of-content-types-movies-vs-tv-shows)
    - [Release Year vs. Duration Scatter Plot](#release-year-vs-duration-scatter-plot)
    - [Count of Movie Genres](#count-of-movie-genres)
    - [Genre vs. Movie Duration Scatter Plot](#genre-vs-movie-duration-scatter-plot)
    - [Distribution of Movie Durations](#distribution-of-movie-durations)
4. [Explanation of some common ratings:](#explanation_of_some_common_ratings)
5. [Conclusion](#conclusion)

## Introduction 🚀

_Netflix_ is a significant platform for entertainment, and understanding the factors influencing viewership can provide valuable insights for both content creators and subscribers. In this project, we employ data analysis techniques to explore trends in Netflix viewership based on various attributes such as genre, duration, and user ratings.

## Dataset Exploration 📊

### Data Overview

The dataset comprises information about Netflix content, including attributes such as show type, title, director, cast, country, release year, rating, duration, and genre. Exploring and preprocessing this data is the initial step in deriving insights and building effective analysis and recommendation models.

- Data Size: The dataset comprises 8807 rows and 12 columns, offering a substantial amount of information for analysis.
- Data Types: The dataset features a mix of data types, including int64 and object.
- Missing Values: Several columns contain missing values, with "director," "cast," "country," "date_added," "rating," and "duration" exhibiting varying degrees of missingness. Addressing missing values is crucial for robust analysis.
- Unique Values: The dataset contains 0 duplicate values, indicating that each row represents distinct information, eliminating redundancy.
- Irrelevant Features: While most features appear relevant, "show_id" and "date_added" are potentially irrelevant for analysis and could be excluded from further evaluation.

### Data Preprocessing

- In the data preprocessing phase, we first examined the shape of the data to understand its dimensions.
- Next, we checked for null values in the dataset and removed them if any were found.
- Additionally, we performed a check for duplicate values and replaced them to ensure data integrity.
- To gain insights into the relationships between different variables, we visualized the correlation map using a heatmap. This visualization allowed us to identify patterns and dependencies among the features in the dataset, helping us understand the interplay between various attributes.

## Exploratory Data Analysis (EDA) 📈

Exploratory Data Analysis involves visualizing and interpreting the dataset to extract meaningful insights. Let's explore some key aspects:

The 'type' column in the Netflix DataFrame contains two distinct values:

- "Movie": Represents content classified as movies.
- "TV Show": Represents content classified as TV shows.

### Missing Value Bar Graph

![Data Distributions](movie_charts/Missing%20Value%20Bar%20Graph.png)

### Distribution of Content Types: Movies vs. TV Shows

![Distribution of Content Types: Movies vs. TV Shows](movie_charts/Distribution%20of%20Content%20Types_%20Movies%20vs_%20TV%20Shows.png)

### Release Year vs. Duration Scatter Plot

![Release Year vs. Duration Scatter Plot](movie_charts/Release%20Year%20vs_%20Duration%20Scatter%20Plot.png)

### Count of Movie Genres

![Count of Movie Genres](movie_charts/Count%20of%20Movie%20Genres.png)

### Genre vs. Movie Duration Scatter Plot

![Genre vs. Movie Duration Scatter Plot](movie_charts/Genre%20vs_%20Movie%20Duration%20Scatter%20Plot.png)

### Distribution of Movie Durations

![Distribution of Movie Durations](movie_charts/Distribution%20of%20Movie%20Durations.png)

## Explanation of some common ratings 📉

- TV-MA: Intended for mature audiences and may contain strong language, sexual content, violence, and other mature themes.
- TV-14: May contain content unsuitable for children under 14, including moderate violence, sexual content, and strong language.
- R: Restricted rating, indicating that viewers under 17 require accompanying parent or adult guardian due to mature content, including violence, language, and sexual content.
- PG-13: Parental guidance suggested for children under 13; may contain some material inappropriate for children under 13, such as moderate violence, language, and thematic elements.
- TV-PG: Parental guidance suggested; may contain material unsuitable for younger children, including mild violence and suggestive content.
- PG: Parental guidance suggested; some material may not be suitable for children, including mild language and thematic elements.
- TV-G: Suitable for all ages; contains little to no violence, strong language, or other potentially offensive content.
- TV-Y: Suitable for all children; contains content appropriate for young children, with no offensive material.
- TV-Y7: Intended for children age 7 and older; may contain mild fantasy violence or comedic elements.
- NR: Not rated; the content rating has not been assigned or is unknown.
- G: General audiences; suitable for all ages, with no offensive content.
- TV-Y7-FV: Intended for children age 7 and older, with fantasy violence.
- UR: Unrated; similar to NR, indicating that the content rating has not been assigned or is unknown.
- NC-17: Not suitable for children under 17; contains explicit content, including graphic violence, sexual content, and language.

## Conclusion 🎉

In this project, I embarked on an exploratory analysis of Netflix TV series and movies, aiming to uncover insights into viewership patterns and trends over time. By examining a dataset containing various attributes such as ratings, duration, and release year, I gained valuable insights into the content landscape of Netflix.

Through my analysis, I discovered several key findings:

- Content Distribution
I observed a diverse range of content types on Netflix, including movies and TV shows. The distribution of content types provides valuable insights into the platform's content strategy and audience preferences.

- Genre Preferences
Analyzing the count of movie genres revealed popular genres among Netflix viewers. Understanding genre preferences can aid content creators and platform managers in curating a compelling content library.

## Temporal Trends
By visualizing the release year vs. duration scatter plot, I identified temporal trends in content production. These trends can inform decision-making regarding content acquisition and production strategies.

## Viewer Engagement
Exploring viewer engagement through scatter plots helped me understand the relationship between genre, duration, and viewer interest. These insights are crucial for optimizing content recommendations and enhancing viewer engagement.

Overall, my exploratory analysis provides valuable insights into the content landscape of Netflix and offers a foundation for further in-depth analysis and modeling. By leveraging data-driven insights, content creators, platform managers, and stakeholders can make informed decisions to enhance the Netflix viewing experience and drive business success.
