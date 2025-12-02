# Twitter Sentiment Analysis — NLP Data Project
This project performs sentiment analysis on a real Twitter dataset.
It demonstrates core data-analytics and NLP skills: data cleaning, preprocessing, feature engineering, visualization, and classification.

## Project Overview  
The goal of this project is to analyze public tweets and determine whether their sentiment is Positive, Negative, Irrelevant, or Neutral.
This project was developed as part of a Data Analytics internship task and showcases:
- Data wrangling & exploration
- Text cleaning and preprocessing
- Stemming and stop-word removal
- Sentiment scoring using TextBlob
- Data visualization
- Insight extraction

## Dataset

The dataset used is twitter_training.csv, containing:

| Column	| Description |
|:---:|:---:|
| ID | Unique tweet ID |
| Category | Labeled sentiment |
| Entity | Topic |
| Tweet | The actual tweet text |

## Technologies Used  
- Python  
- Pandas
- Numpy
- Matplotlib
- Seaborn
- NLTK (stopwords, tokenization, stemming)
- TextBlob (sentiment polarity)
- Jupyter Notebook

## Data Cleaning & Preprocessing
Steps performed:
1. Removed unwanted characters and punctuation
2. Converted text to lowercase
3. Tokenized sentences
4. Removed stopwords
5. Applied stemming using PorterStemmer
6. Reconstructed cleaned sentences
7. Calculated sentiment polarity scores

## Visualizations

The project includes visual insights such as:
- Sentiment distribution
- Word frequency analysis
- Polarity score plots
These help understand the emotional tone of tweets.

## Sentiment Classification

Using TextBlob, each tweet is assigned:
- Positive sentiment
- Negative sentiment
- Neutral sentiment
Results are stored in new columns for easy interpretation.

## Key Insights

- Many tweets exhibited negative tone (common in public feedback).
- Cleaned text greatly improved sentiment consistency.
- Stemming reduced vocabulary size and improved classification clarity.

## How to Run
1. Install packages
```bash
  pip install pandas numpy nltk textblob matplotlib seaborn
```
2. Open & Run
```bash
  P1 M2.ipynb
```   
