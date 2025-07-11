# Sentiment-Analysis

Sentiment Analysis on Amazon Reviews
This project compares two sentiment analysis approaches on the Amazon Fine Food Reviews dataset:

VADER – a rule-based model using lexical heuristics

RoBERTa – a transformer-based model (cardiffnlp/twitter-roberta-base-sentiment)

We applied both models to 1000 reviews and visualized their sentiment scores (neg, neu, pos) against actual star ratings.

🔍 Key Observations
VADER scores correlate linearly with ratings but struggle with nuance.

RoBERTa provides sharper, context-aware sentiment predictions.

Differences are most visible in mid-range ratings (2–4 stars).

📈 Output
A pairplot shows how each model's sentiment outputs vary across review scores.

This work was inspired by Robert Mulla’s sentiment analysis tutorial.
