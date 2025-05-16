## 📌 Project Overview

This project explores the use of Natural Language Processing (NLP) to support and enhance video game development. By mining and analyzing player reviews, the goal is to uncover trends, extract sentiments, and derive insights that inform strategic decisions in game design, marketing, and feature prioritization.

We applied machine learning and NLP techniques on review data from the Steam platform, allowing us to evaluate player sentiment, identify key discussion topics, and model user preferences—tools that game developers can use to align design choices with community feedback.

## 📂 Contents

- `NLP_Project.ipynb` – Main notebook demonstrating data loading, preprocessing, sentiment analysis, and visualization of insights.
- Review text mining and word cloud generation
- Sentiment analysis using **VADER** and **TextBlob**
- Topic frequency and term visualization
- Predictive modeling preparation (e.g., sentiment vs. review helpfulness)

## 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- `TextBlob`, `VADER` – Sentiment analysis
- `WordCloud` – Visualization of frequent terms
- `Pandas`, `Matplotlib`, `Seaborn` – Data manipulation and plotting
- Steam game reviews dataset (synthetically prepared for this analysis)

## 🚀 How to Run

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install textblob vaderSentiment wordcloud pandas matplotlib seaborn
