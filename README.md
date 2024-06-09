# Subtheme_senti_analysis
Overview
This Python script performs sentiment analysis on textual data, extracting key phrases and determining the sentiment of each review. It employs natural language processing (NLP) techniques using spaCy and TextBlob libraries.

Features
Key Phrase Extraction: Extracts main subjects and actions from each sentence to represent the essence of the review.
Sentiment Analysis: Determines the sentiment (positive or negative) of each review using TextBlob's polarity scores.
Readability: Well-structured code with clear comments and explanations for easy understanding and modification.

Requirements
Python 3.x
Required Python libraries: spaCy, TextBlob, NLTK

Installation
Install Python 3.x if not already installed.
Install required Python libraries:
Copy code
pip install spacy textblob nltk
python -m spacy download en_core_web_sm

Clone or download the script files from this repository.

Usage
Ensure that the input data (e.g., reviews) is in a format supported by the script (e.g., CSV file with reviews in the first column).

Run the script:
Copy code
python sentiment_analysis.py
Follow the on-screen instructions to input the path to the dataset containing reviews.

Output
The script generates an output dataframe containing the reviews, their respective subthemes, and sentiments.

Approach
The script adopts a simplistic approach to sentiment analysis by extracting key phrases representing the main subjects and actions of each review. It utilizes existing NLP libraries like spaCy and TextBlob for key phrase extraction and sentiment analysis, respectively. The approach prioritizes simplicity, innovation, and contemporary relevance, offering a modern and accessible solution for sentiment analysis tasks.

Shortcomings and Future Improvements
The key phrase extraction method may overlook complex relationships within the text. Future improvements could involve incorporating more sophisticated NLP techniques for richer key phrase extraction.
TextBlob's sentiment analysis may not capture subtle nuances in sentiment. Enhancements could include training custom sentiment analysis models or integrating more advanced sentiment analysis techniques.


