# MLPT_Project
Project for the course Machine Learning for Portfolio Management and Trading


This project aims at blending financial report analysis and machine learning to predict stock market trends, focusing on diversified investments across five key sectors: Banking, Real Estate, Automobile, Energy, and Tourism. Leveraging both a traditional Markowitz portfolio optimization model and an innovative sentiment analysis of the Federal Reserve's Beige Book reports, the project aims to refine investment strategies by prioritizing sectors highlighted as economically robust. This dual approach not only utilizes quantitative market data but also incorporates qualitative insights from authoritative sources.

## Key Features

- Data Scraping: Automated scraping of the Beige Book reports, focusing on the National Summary and the New York district, spanning from 2014 to 2022.
- Sentiment Analysis: Utilizes NLP techniques to perform sentiment analysis on the scraped Beige Book text, identifying sector-specific sentiments.
- Financial Data Integration: Incorporation of quantitative trading data, leveraging yfinance to fetch historical market prices.
- Predictive Modeling: Development of a machine learning model that integrates sentiment scores with market data to predict stock movements.
- Markowitz Portfolio Optimization: Application of the Markowitz portfolio theory, modified by sentiment analysis, to optimize trading strategies.
- Backtesting: Comprehensive backtesting framework to evaluate the performance of the predictive trading strategy against benchmarks.