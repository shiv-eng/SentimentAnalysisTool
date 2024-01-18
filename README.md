# Sentiment Analysis Tool

## Overview
A simple Sentiment Analysis web application built with Flask and NLTK's VADER. Analyze the sentiment of text input and get a sentiment score.

## Dependencies
- Python
- Flask
- NLTK

## Installation

git clone https://github.com/shiv-eng/SentimentAnalysisTool.git
cd SentimentAnalysisTool
pip install -r requirements.txt

## Usage
python app.py

Access the app at http://127.0.0.1:5000/. Enter text in the input field and click on the "Analyze" button to get the sentiment analysis result.

# Features

- **Input Field:** Enter text for sentiment analysis.
- **Sentiment Analysis:** Uses NLTK's VADER to analyze sentiment.
- **Result Display:** Shows the sentiment score and categorized sentiment (Positive, Negative, or Neutral).

# Files

- `app.py`: Flask application script.
- `templates/index.html`: HTML template for the web interface.


# Acknowledgments

- [Flask](https://flask.palletsprojects.com/)
- [NLTK](https://www.nltk.org/)

Feel free to contribute or report issues!



