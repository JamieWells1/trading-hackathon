# 🏆 Hackathon Winners: Rundown of Top Submissions

A record of the January trading hackathon, which required participants to create the best performing Python trading strategy!

## 🥇 1st Place: Abdul

Abdul created a sentiment analysis-based trading strategy that analyzed financial news to determine market sentiment and make trading decisions. His approach included:

### News Data Integration:

Pulled real-time financial news data using the yfinance API.

### Sentiment Analysis:

Leveraged Natural Language Processing (NLP) to classify news articles as positive, neutral, or negative using pre-trained .keras and .h5 models.
Incorporated libraries such as TextBlob or NLTK to preprocess and analyze the sentiment of financial articles.

### Trading Logic:

Generated buy/sell signals based on the aggregated sentiment score:
    - Positive Sentiment: Triggered buy signals.
    - Negative Sentiment: Triggered sell signals.
    
### Backtesting:

Evaluated the strategy's performance against historical market data to fine-tune the sentiment thresholds and improve accuracy.

Abdul’s submission stood out for its innovative use of NLP in a trading context, integrating financial news analysis with actionable trading signals. His strategy demonstrated a strong understanding of both financial markets and advanced machine learning techniques.
