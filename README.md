# 📈 News Sentiment Driven price prediction

Welcome to the **News Sentiment & Stock Movement Analysis** project! This repository explores the relationship between financial news sentiment and stock price movements. The goal is to leverage natural language processing (NLP) and quantitative analysis to develop data-driven investment strategies.

---

## 🌟 Project Overview

**Business Objective:**  
Nova Financial Solutions aims to enhance predictive analytics capabilities by analyzing how news sentiment impacts stock prices. This project involves:

- Sentiment analysis of news headlines
- Correlation analysis between sentiment and daily stock returns
- Exploratory Data Analysis (EDA) to uncover patterns and insights

---

## 📂 Repository Structure

├── .vscode/

│   └── settings.json

├── .github/

│   └── workflows

│       ├── ci.yml

├── .gitignore

├── requirements.txt

├── README.md

├── src/

│   ├── __init__.py

├── notebooks/

│   ├── __init__.py

│   └── README.md

├── tests/

│   ├── __init__.py

└── scripts/

│   ├──  __init__.py

│   └── README.md

## 🧪 Key Features
✅ Exploratory Data Analysis (EDA)

    - Descriptive statistics (headline length, article frequency, publisher activity)
    - Time series analysis of news publication frequency
    - Text analysis: keyword extraction and topic modeling
    - Publisher analysis

Calculates a sentiment score between -1 (negative) and 1 (positive)

## ✅ Quantitative Analysis

- Aggregates daily sentiment scores 
- Computes daily stock returns (% change)
- Calculates Pearson correlation between sentiment and returns

## ✅ Visualization

- **Publication Trends:** Line plots display the frequency of news articles published over time, highlighting peaks around trading hours and periods of increased market activity.
- **Sentiment Distributions:** Histograms and boxplots show the distribution of sentiment scores, revealing the prevalence of neutral, positive, or negative news.
- **Correlation Analysis:** Scatter plots and heatmaps visualize the relationship between aggregated sentiment scores and daily stock returns, indicating moderate positive correlations.
- **Publisher Activity:** Bar charts compare the number of articles and sentiment contributions from different publishers.

These visualizations provide actionable insights into how news sentiment and publication patterns relate to stock price movements.

## 📈 Results & Insights

- **Moderate Correlation:** Daily aggregated news sentiment showed a moderate positive correlation with daily stock returns across multiple stocks.
- **Publisher Influence:** High-frequency publishers contributed significantly to overall sentiment trends, with some publishers consistently skewing sentiment positive or negative.
- **Timing Patterns:** News publication activity peaked during pre-market and trading hours, aligning with periods of increased market volatility.
- **Sentiment Distribution:** Most headlines were neutral, but spikes in positive or negative sentiment often preceded notable price movements.
- **Predictive Potential:** Combining sentiment scores with historical price data improved short-term return prediction accuracy in baseline models.

These findings highlight the value of integrating news sentiment analysis into quantitative trading strategies.

## 🚀 Next Steps

- Enhance sentiment analysis using advanced deep learning models such as BERT or RoBERTa.
- Integrate real-time news feeds and live stock price data for up-to-date analysis.
- Develop an interactive dashboard to dynamically visualize sentiment, stock movements, and correlations.
- Expand analysis to include additional financial instruments and alternative data sources.
- Improve model interpretability and backtest predictive strategies on historical data.
- Collaborate with domain experts to refine features and validate findings.
- Document and automate the workflow for reproducibility and scalability.


## 📧 Contact
For questions, feedback, or contributions, please reach out to:
Oliyad Teshome Dida
📧 oliyadteshomedida@gmail.com
📱 +251 982152928