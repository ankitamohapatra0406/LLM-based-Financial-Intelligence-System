# 🚀AI-Powered Financial Intelligence System

An end-to-end **LLM-based financial analytics platform** that combines social media sentiment, financial news, and stock market data to generate actionable insights for decision-making.


## 📌Overview
This system uses transformer-based models such as BERT, FinBERT, and RoBERTa to analyze financial text data and correlate sentiment with real-time stock trends.

## Key Features
* **Sentiment Analysis:** Classifies financial text as bullish, bearish, or neutral
* **News Summarization:** Generates concise summaries of financial articles
* **Trend Detection:** Tracks sentiment over time and identifies patterns
* **Stock Correlation:** Compares sentiment signals with price movements
* **API Deployment:** FastAPI-based endpoints for model inference
* **Dashboard:** Visualizes sentiment, trends, and market data

## Architecture
Data Sources - NLP Models - Insight Engine - FastAPI - Backend - Dashboard

## Tech Stack
* Python, FastAPI
* Transformers (HuggingFace)
* Pandas, NumPy
* React / Streamlit

## ▶️ Run
```bash
uvicorn api.main:app --reload
```

## Use Cases

* Market sentiment analysis
* Financial trend monitoring
* Decision support for trading


