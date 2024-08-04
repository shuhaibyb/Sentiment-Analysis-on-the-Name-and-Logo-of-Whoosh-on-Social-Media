# Sentiment Analysis on the Name and Logo of Whoosh on Social Media

This repository contains code and data for conducting sentiment analysis on the name and logo of Whoosh on social media platforms such as Twitter and Instagram.

## Files and Descriptions

1. **crawl_data_twitter.ipynb**
   - This notebook is used to scrape data from X (formerly known as Twitter). It contains the code necessary to collect tweets that mention the name and logo of Whoosh.

2. **concat_data_twitter.ipynb**
   - This notebook is used to concatenate the data collected from Twitter. It combines multiple data files into a single dataset for further analysis.

3. **data.xlsx**
   - This Excel file contains three sheets:
     - **twitter:** This sheet includes data collected from Twitter.
     - **instagram:** This sheet includes data collected from Instagram.
     - **normalisasi:** This sheet contains the normalization dictionary used for preprocessing the text data.

4. **stopwords**
   - This file contains a list of stopwords used to remove common words that do not contribute significantly to sentiment analysis.

5. **preprocessing_modelling_and_prediction.ipynb**
   - This notebook is used for preprocessing the data, building sentiment analysis models, and predicting sentiment for Instagram data using the trained models. It includes all necessary steps from data cleaning to model evaluation and prediction.
