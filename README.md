**Overview**
This project is a sentiment analysis tool designed to explore potential correlations between public news sentiment and Nvidia's stock price over a specific period (February 5, 2025, to March 5, 2025). By leveraging financial data from Yahoo Finance (via yfinance) and news data from the News API, the tool analyzes news headlines using the VADER sentiment analysis model to compute sentiment scores. These scores are then merged with Nvidia stock price data and visualized to identify any observable relationships between sentiment and stock price movements.

The current implementation focuses on news data, but the framework is extensible to include additional sources such as Reddit or other social media platforms in the future.

**Project Goals**
Analyze Sentiment: Use VADER (Valence Aware Dictionary and sEntiment Reasoner) to calculate sentiment scores from news headlines related to Nvidia.
Correlate with Stock Price: Merge sentiment scores with Nvidia stock price data to investigate potential correlations.
Visualize Results: Create a dual-axis plot showing Nvidia stock prices alongside aggregated sentiment scores over time.

**Prerequisites**
To run this project, you'll need the following:

- **Python 3.8 or higher**
- **Required Python libraries** (install via pip):
  - `yfinance`
  - `nltk`
  - `vaderSentiment`
  - `requests`
  - `pandas`
  - `matplotlib`
- **A News API key** (sign up at [NewsAPI.org](https://newsapi.org) to obtain one)

**Installation**
  1. Clone the Repository
  2. Install Dependencies: pip install yfinance nltk vaderSentiment requests pandas matplotlib
  3. Add News API Key: api_key = 'your_news_api_key_here'
  4. Run the Script: Execute the Jupyter notebook

**Results**

The generated plot illustrates:
1. Nvidia stock closing prices (blue line) ranging from approximately $80 to $150.
2. Aggregated sentiment scores (green/red bars) ranging from -0.5 to 4, indicating daily sentiment trends.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgments**
- VADER Sentiment for sentiment analysis.
- Yahoo Finance and News API for data sources.
  
