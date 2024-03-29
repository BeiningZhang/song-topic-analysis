# Song Topic Cluster Analysis: Unveiling Musical Trends

## Overview

This project focuses on analyzing song lyrics to uncover underlying topics and trends in the music industry. It involves data extraction, cleaning, exploratory data analysis (EDA), sentiment analysis, and topic clustering using Latent Dirichlet Allocation (LDA) modeling.

## Requirements

To run the code, you need to have Python installed along with the following libraries:

- pandas
- nltk
- gensim
- scikit-learn
- seaborn
- matplotlib
- wordcloud

You can install these libraries using pip:

```bash
pip install pandas nltk gensim scikit-learn seaborn matplotlib wordcloud
```

## Data Extraction

The lyrics data is extracted from text files in the provided folders. A DataFrame is created with columns for song names and lyrics.

## Data Cleaning

Blank files and songs with duplicated lyrics are removed. Data cleaning involves handling missing data and ensuring data integrity.

## Exploratory Data Analysis (EDA)

EDA includes analyzing features such as rhyming lines, song names appearing in lyrics, and sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).

## Sentiment Analysis

Sentiment analysis is performed using the VADER library to classify lyrics as negative, neutral, or positive.

## Topic Clustering

Topic clustering is conducted using Latent Dirichlet Allocation (LDA) topic modeling. The optimal number of topics is determined based on perplexity and coherence scores.

## Interpretation of Clusters

The identified topics are interpreted based on the most frequent words in each cluster.

## Prediction

New songs are classified into topics using the trained LDA model.

## Results

The results of the analysis, including identified topics and sentiment analysis, are presented in the code output and visualizations.

## Limitations

- Fixed number of topics
- Bag of words approach
- Lack of sufficient data
- Limited vocabulary
- Unstable results
- Difficulty in interpreting topics

## Future Work

- Hyperparameter tuning for improved topic modeling
- Exploring alternative topic modeling techniques
- Combining LDA with other clustering methods for better results

## Conclusion

This project provides insights into musical trends and themes by analyzing song lyrics. It offers a framework for understanding the underlying patterns in music and potential applications in the music industry.
