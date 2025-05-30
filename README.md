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

├── .github/

│ └── workflows/

│ └── unittests.yml

├── notebooks/

│ ├── eda.ipynb

├── src/

│ ├── data_loader.py

│ ├── sentiment_analysis.py

│ ├── correlation_analysis.py

├── tests/

│ ├── test_data_loader.py

│ ├── test_sentiment_analysis.py

│ ├── test_correlation_analysis.py

├── scripts/

│ ├── run_eda.py

│ ├── run_analysis.py

├── requirements.txt

├── README.md

└── .gitignore

## 🧪 Key Features
✅ Exploratory Data Analysis (EDA)
Descriptive statistics (headline length, article frequency, publisher activity)

Time series analysis of news publication frequency

Text analysis: keyword extraction and topic modeling

## ✅ Sentiment Analysis
Uses TextBlob and nltk for headline sentiment scoring

Calculates a sentiment score between -1 (negative) and 1 (positive)

## ✅ Quantitative Analysis
Computes daily stock returns (% change)

Aggregates daily sentiment scores

Calculates Pearson correlation between sentiment and returns

## ✅ Visualization
Plots to visualize publication trends, sentiment distributions, and correlations

Scatter plots showing the relationship between news sentiment and stock movement

## 📈 Results & Insights
Average daily sentiment was moderately correlated with daily stock returns.

Publishers with higher frequency had a stronger impact on sentiment trends.

Publication times revealed peaks around trading hours.

These insights can be leveraged to build predictive models and design investment strategies based on news sentiment.

## 🚀 Next Steps
Enhance sentiment analysis with deep learning models like BERT.

Integrate real-time news feeds and live stock data.

Develop an interactive dashboard to visualize and monitor correlations dynamically.


## 📧 Contact
For questions, feedback, or contributions, please reach out to:
Oliyad Teshome Dida
📧 oliyadteshomedida@gmail.com
📱 +251 982152928