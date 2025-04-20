# Indian-Election-Sentiment-Analysis--NLP
This project performs sentiment analysis on tweets about Narendra Modi and Rahul Gandhi using TextBlob. It filters neutral tweets, samples data for balance, and visualizes positive vs negative sentiment distribution with Plotly.

# Sentiment Analysis of Tweets: Modi vs Rahul

This project analyzes public sentiments in tweets related to Indian politicians Narendra Modi and Rahul Gandhi. It uses TextBlob to calculate polarity scores, classifies tweets into Positive, Negative, and Neutral categories, and visualizes the results with bar charts.

## Features
- Sentiment analysis using TextBlob
- Classification of tweets into Positive, Negative, and Neutral
- Removal of neutral tweets for focused comparison
- Random sampling to balance datasets
- Visualization using Plotly

## Dataset
- `modi_reviews.csv` and `rahul_reviews.csv` contain tweets related to the respective politicians.

## Workflow
1. Read and preprocess tweets
2. Calculate polarity using TextBlob
3. Classify tweets based on polarity scores
4. Remove neutral tweets
5. Balance the datasets using random sampling
6. Group and count sentiment labels
7. Visualize sentiment distribution for each politician

## Technologies Used
- Python
- Pandas
- Numpy
- TextBlob
- Plotly

## How to Run
1. Ensure Python is installed.
2. Install dependencies:
   ```bash
   pip install pandas numpy textblob plotly
