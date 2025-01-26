# 🏆 Hackathon Winners: Rundown of Top Submissions

A record of the January trading hackathon, which required participants to create the best performing Python trading strategy!

## 🥇 1st Place: Abdul

Abdul created a sentiment analysis-based trading strategy that analyzed financial news to determine market sentiment and make trading decisions. His approach included:

### News Data Integration:

Pulled real-time financial news data using the yfinance API.

### Sentiment Analysis:

Leveraged Natural Language Processing (NLP) to classify news articles as positive, neutral, or negative using pre-trained .keras and .h5 models.
Incorporated libraries such as TextBlob or NLTK to preprocess and analyze the sentiment of financial articles.

### Trading Logic:

Generated buy/sell signals based on the aggregated sentiment score:

- Positive Sentiment: Triggered buy signals.
- Negative Sentiment: Triggered sell signals.

Abdul’s submission stood out for its innovative use of NLP in a trading context, integrating financial news analysis with actionable trading signals. His strategy demonstrated a strong understanding of both financial markets and advanced machine learning techniques.

---

## 🥈 2nd Place: (Tobi)[https://www.linkedin.com/in/oluwatobi-s/]

Tobi developed an effective momentum reversion hybrid strategy that utilized a combination of moving averages and mean reversion principles. His approach included:

- Calculating moving averages and mean prices for both long-term and short-term windows.
- Establishing thresholds to identify overbought or oversold conditions:
    - Buy Signal: When the price drops significantly below the calculated mean.
    - Sell Signal: When the price rises significantly above the calculated mean.
- Incorporating a hybrid of momentum and mean-reversion techniques to ensure the strategy could adapt to varying market conditions.

Tobi’s strategy demonstrated a well-thought-out blend of quantitative techniques, clear logic, and simplicity.

---

## 🥉 3rd Place: Kobichukwura

Kobichukwura, a non-technical participant, submitted a PowerPoint presentation outlining a conceptual strategy. His submission included:

### Entry criteria:
- Buy when stock prices drop by more than 5%.
- Use technical indicators like RSI and moving averages to confirm buy signals.

### Exit criteria:
- Sell if stock prices drop by 5% after purchase.
- Implement the **golden cross** (shorter-term moving average crossing above a longer-term moving average) as a buy signal and the **death cross** (shorter-term moving average crossing below a longer-term moving average) as a sell signal.

Despite not submitting code, Kobichukwura demonstrated exceptional effort by providing a detailed, well-reasoned strategy. His focus on combining multiple indicators showed a clear understanding of trading principles and creativity in presenting ideas.

---

## Honorable Mentions

We want to thank all participants for their hard work, creativity, and dedication throughout the hackathon. Your efforts truly made this event a success, and we look forward to seeing what you create in the future!
