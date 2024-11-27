# Airline Reviews Sentiment Analysis 

This is an exploratory and comparitive analysis of various features in multiple airlines.
- The insights help improvise the business by focusing on the areas of improvement.
- NLTK is used for processing the text based reviews and derive the positive, negative/neutrl sentiment.
- A comparitive analysis is performed to compare the top 10 airlines in multiple features and what could be improvised
- Libraries Used: Matplotlib, seaborn, Pandas, Numpy, Scikit learn

# Project Overview

The dataset contains reviews and ratings for various airlines, including sentiment ratings for different aspects like service, food, and entertainment. Using this data, the project performs:
- Sentiment analysis on the reviews to classify them as positive, negative, or neutral.
- Data preprocessing, cleaning, and feature extraction for better analysis.
- Visualization of various patterns, such as the correlation between ratings, and trends in airline reviews over time.
- Statistical analysis and insights into customer satisfaction.

# Libraries Used
- **pandas**: Data manipulation and analysis.
- **seaborn**: Data visualization and statistical plotting.
- **matplotlib**: Plotting graphs.
- **nltk**: Natural Language Toolkit for text preprocessing and sentiment analysis.
- **sklearn**: Machine learning for model building and evaluation.
- **numpy**: Numerical operations.

# Requirements
Before running the code, ensure the necessary libraries installed. You can install them using pip and Also, ensure that the dataset, AirlineReviews.csv, placed in the correct directory for the script to load it.

# Data Preprocessing
- **Handling Missing Data**: The script identifies missing values in the dataset and handles them accordingly.
- **Text Cleaning**: The reviews are preprocessed by removing non-alphanumeric characters, tokenizing the text, and removing stopwords.
- **Sentiment Analysis**: Sentiment labels (Positive, Negative, Neutral) are assigned to each review using the VADER sentiment analysis tool. The sentiment score is also calculated for each review.
- **Feature Extraction**: Additional features like MonthYearPublished are extracted for time-based analysis.

# Visualizations
Several visualizations are created to explore the data:
- **Sentiment Distribution**: Pie chart showing the distribution of positive, negative, and neutral reviews.
- **Review Sentiment vs. Ratings**: Heatmaps and bar charts comparing various ratings (Food, Service, etc.) and overall sentiment.
- **Airline Performance**: Bar charts showing airlines with the best and worst ratings in different categories (e.g., Best Wifi, Best Service).
- **Trends Over Time**: Line plots showing how review scores and sentiment change over time.
- **Correlation Analysis**: Heatmap of correlations between various ratings.

# Insights
The sentiment analysis reveals that a majority of the reviews are positive, with a substantial number of neutral and negative reviews as well.
Correlations between ratings (e.g., food, service) indicate which factors most influence the overall score.
Airline rankings are also derived based on various rating criteria, helping identify top-performing airlines.
