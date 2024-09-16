# F1 Named Entity Sentiment Analysis

This Jupyter notebook performs sentiment analysis on Formula 1-related content from Reddit using natural language processing techniques.

## Key Features

- Scrapes top posts and comments from F1-related subreddits using PRAW
- Performs named entity recognition (NER) on the collected text data
- Conducts sentiment analysis on titles, post content, and comments
- Standardizes and cleans entity names for consistency
- Visualizes sentiment analysis results for top F1 personalities

## Main Components

1. Data Collection: Asynchronously fetches posts and comments from r/formula1, r/F1Technical, and r/formuladank
2. Text Processing: Cleans and prepares text data for analysis
3. Named Entity Recognition: Identifies and extracts person names from the text
4. Sentiment Analysis: Determines sentiment (positive, neutral, negative) for each text segment
5. Data Standardization: Normalizes entity names to account for variations and misspellings
6. Visualization: Creates a bar plot showing average sentiment for top F1 personalities

## Requirements

- Python 3.x
- Libraries: asyncpraw, pandas, transformers, torch, sklearn, matplotlib, seaborn

## Usage

Run the notebook cells sequentially to collect data, perform analysis, and generate visualizations. The final output includes a bar plot of sentiment analysis results and a CSV file with comprehensive analysis data.

## Note

Ensure you have the necessary API credentials for Reddit access and respect rate limits when scraping data.
