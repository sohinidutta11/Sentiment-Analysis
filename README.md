# Sentiment-Analysis

## Sentiment Analysis on Amazon Reviews
This project compares two sentiment analysis approaches on the Amazon Fine Food Reviews dataset:

- VADER – rule-based sentiment scoring using lexical heuristics

- RoBERTa – transformer-based model: cardiffnlp/twitter-roberta-base-sentiment

- Both models were applied to 1,000 reviews, and their sentiment scores were compared to actual user ratings (1–5 stars).

## Key Observations
- VADER scores (neg, neu, pos, compound) track well with extreme ratings but misclassify subtle/mixed sentiment.

- RoBERTa produces more confident, context-aware predictions with sharper separation between sentiments.

- Biggest model disagreements occur on mid-range reviews (2–4 stars), highlighting their different approaches.

## Output Visualization
- A seaborn.pairplot was used to visualize sentiment score distributions for both models across star ratings.

- Shows strong correlation for both models at extreme scores, but RoBERTa outperforms in nuanced cases.

## Acknowledgment
This project was inspired by [Robert Mulla’s Sentiment Analysis tutorial](https://www.youtube.com/watch?v=QpzMWQvxXWk) on YouTube.

