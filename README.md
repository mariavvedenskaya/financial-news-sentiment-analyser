# Company News Sentiment Analyser

An AI-powered web app that analyses the sentiment of live news headlines for any company, built with Python and deployed on Streamlit Cloud.

Live demo: https://company-news-sentiment-analyser.streamlit.app/

## What it does
- Fetches recent news headlines for any company using the NewsAPI
- Runs each headline through **FinBERT**, an AI model specifically trained on financial text
- Classifies each headline as positive, negative, or neutral
- Displays an overall sentiment score, a colour-coded list of clickable headlines, and a sentiment breakdown chart

Filters results to the last 30 days, sorted from most recent

## Why I built this
I built this project to develop practical AI and Python skills relevant to finance and fintech roles. It demonstrates how natural language processing can be applied to real-world text data, a technique used by quantitative analysts and fintech companies to gauge market sentiment.

## Tech stack
- Python
- [FinBERT](https://huggingface.co/ProsusAI/finbert) - NLP model trained on financial text
- Streamlit - web app framework
- NewsAPI - live news data
- Pandas - data processing
- Altair 
