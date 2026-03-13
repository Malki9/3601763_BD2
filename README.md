# 3601763_BD2
# JC Penney Customer Review Analysis

## Overview
This project analyses customer reviews and product data from JC Penney to understand customer sentiment, product performance, and customer behaviour. The analysis explores whether customer rating scores accurately reflect the sentiment expressed in the review text.

## Objectives
- Explore customer review and product datasets
- Perform exploratory data analysis (EDA)
- Analyse sentiment in review text using the VADER sentiment analysis model
- Compare rating sentiment with review text sentiment
- Train a Logistic Regression model to evaluate whether sentiment can be predicted from review text
- Generate insights that can support business decision-making

## Datasets
The following datasets were used in this analysis:

- **users.csv** – customer demographic information
- **products.csv** – product details including price and average score
- **reviews.csv** – customer reviews and rating scores
- **jcpenney_products.csv** – extended product dataset
- **jcpenney_reviewers.json** – customer review history

## Methods Used
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Sentiment Analysis (VADER)
- TF-IDF vectorization
- Logistic Regression classification
- Confusion matrix evaluation

## Key Findings
- A large mismatch exists between customer ratings and review text sentiment.
- Logistic Regression achieved moderate predictive performance, indicating noisy labels in the dataset.
- Customer satisfaction appears to depend more on product experience than price.
- LIZ CLAIBORNE is most liked brand and STAFFORD is most disliked brand.
- Majority of the consumers loved the fit, quality and price for top brands.
- Majority of customers experience issues in sizing and quality of the products 

## Running the Project
1. Install the required libraries listed in `requirements.txt`
2. Run the Jupyter Notebook provided in the repository.
3. Ensure all datasets are placed inside the **Data** folder.
