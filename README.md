📊 Sentiment & Topic Analysis of Customer Reviews
This repository contains a complete pipeline for text analysis on customer reviews, including preprocessing, sentiment analysis, and visualization. 
It transforms raw review data into actionable insights using Python, NLTK, TextBlob, and various visualization tools.

🚀 Features
✅ Data Preprocessing

Remove missing values

Lowercasing, cleaning special characters

Tokenization & stopword removal

✅ Sentiment Analysis

Uses TextBlob for polarity scoring

Categorizes reviews as Positive, Negative, Neutral

✅ Topic Modeling

Extracts latent topics

Generates word clouds for each topic

✅ Visualizations

Sentiment distribution pie chart

Word clouds for each topic

🛠️ Tech Stack
Python

pandas

xlrd

nltk

textblob

matplotlib, seaborn, wordcloud

📂 Workflow
Load Data → The flipkart gba_1.ipynb notebook imports your initial Excel file.

Preprocess Text → The first notebook cleans, tokenizes, and removes stopwords from the data.

Save Preprocessed Data → The cleaned data is saved to preprocessed_data.xlsx.

Sentiment Analysis → The flipkart gba_2.ipynb notebook performs sentiment analysis on the preprocessed data.

Topic Modeling → Word clouds are generated to highlight key topics.

Visualizations → Pie charts and word clouds are created to visualize the findings.

▶️ How to Run
Clone this repository.

Make sure you have the required libraries installed:

Bash

pip install pandas xlrd nltk textblob matplotlib seaborn wordcloud
First, run the flipkart gba_1.ipynb notebook to preprocess the data and create the preprocessed_data.xlsx file.

Next, run the flipkart gba_2.ipynb notebook to perform the sentiment and topic analysis and generate the visualizations.
