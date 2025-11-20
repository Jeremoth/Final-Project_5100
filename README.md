# U.S. Spotify Music Emotion & Unemployment Analysis (2017–2020)

This project analyzes how the emotional characteristics of popular music in the United States changed from 2017–2020 and investigates whether these changes relate to shifts in unemployment rates. The analysis integrates Spotify audio features with official U.S. labor statistics to study year-to-year trends, perform statistical testing, and apply time-series modeling.

### 📘 Abstract
This project examines the evolution of musical emotion in the United States using Spotify Top 200 chart data from 2017–2020 and combines it with annual unemployment statistics from the Federal Reserve (FRED). We focus on emotional audio features—particularly valence and energy—as well as lyrics-based sentiment indicators. Through exploratory data analysis, statistical inference, and ARIMA modeling, we evaluate whether changes in national economic conditions correspond to shifts in the emotional tone of mainstream music.

### 📁 Dataset
#### 1. Spotify Kaggle Dataset (2017–2020)

Filtered to USA only. Includes:

Audio features (valence, energy, danceability)

Popularity score (custom weighting)

Genre and metadata

Lyrics-based sentiment scores for English songs

Release dates (used to compute yearly averages)

#### 2. U.S. Unemployment Rate (UNRATE)

Source: Federal Reserve Economic Data
Converted to yearly means for 2017–2020.

### 📊 Methods

This project includes:

#### 1. Exploratory Data Analysis

Trends in valence, energy, and popularity

Scatter plots: musical emotion vs unemployment

#### 2. Statistical Tests

t-tests (year-to-year comparisons)

Chi-square tests (high/low valence vs high/low unemployment)

Bootstrap confidence intervals

ANOVA across years or genres

#### 3. Time Series Analysis

Visualization of yearly trends

ARIMA modeling of musical positivity


### 🎯 Goal

To understand whether emotional trends in U.S. popular music align with changes in national economic conditions.