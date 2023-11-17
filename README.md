# Implementation-of-Sentimental-Analysis
Sentiment analysis is used to detect or recognize the sentiment which is contained in the text. This analysis helps us to get the reference of our text which means we can understand that the content is positive, negative, or neutral. Sentiment analysis, also referred to as opinion mining, is an approach to natural language processing (NLP) that identifies the emotional tone behind a body of text. This is a popular way for organizations to determine and categorize opinions about a product, service or idea. Sentiment Analysis is a use case of Natural Language Processing (NLP) and comes under the category of text classification. To put it simply, Sentiment Analysis involves classifying a text into various sentiments, such as positive or negative, Happy, Sad or Neutral, etc.

## Program:
```
# Reg.no: 212220230015
# Name: DurgaDevi P

import nltk
from nltk.sentiment import SentimentIntensityAnalyzer

nltk.download('vader_lexicon')

sia = SentimentIntensityAnalyzer()

text = input("Enter a sentence to analyze: ")

scores = sia.polarity_scores(text)

print("Positive score:", scores['pos'])
print("Negative score:", scores['neg'])
print("Neutral score:", scores['neu'])
print("Compound score:", scores['compound'])
```
## Output:
![278951044-eb5d65b1-309d-41c2-ab01-c003196577f9](https://github.com/durga46/Implementation-of-Sentimental-Analysis/assets/75235704/7713d0c6-ec3c-45ef-9de6-730f963dc3e3)
