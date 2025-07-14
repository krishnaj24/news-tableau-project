# News Tableau Project

This project analyzes Business and Market news articles scraped from two news websites. It includes data cleaning, sentiment analysis, topic modeling, and visualization in Tableau.

## What This Project Does

- Scrapes news articles from two news websites
- Cleans and processes text data
- Performs sentiment analysis using VADER
- Identifies topics using TF-IDF and Non-negative Matrix Factorization (NMF)
- Visualizes key insights in Tableau

## Project Structure

```
news-tableau-project/
├── data/
│   └── business_market_final.xlsx
├── notebooks/
│   └── news_data_pipeline.ipynb
├── tableau/
│   └── news_dashboard.twbx
├── README.md
```

- **data/** → cleaned dataset for Tableau
- **notebooks/** → Python notebook for scraping and analysis
- **tableau/** → Tableau dashboard with visualizations

## Requirements

- Python 3.x
- pandas
- scikit-learn
- vaderSentiment

Install required Python packages:

```
pip install pandas scikit-learn vaderSentiment
```

## How to Use

1. Run the notebook in `notebooks/news_data_pipeline.ipynb` to reproduce scraping and analysis.
2. Open the Tableau file `tableau/news_dashboard.twbx` in Tableau Desktop to explore the dashboard.

## Notes

- Ensure your working directory matches this folder structure for code paths to work properly.
- The Tableau file includes several charts and a combined dashboard for insights.
