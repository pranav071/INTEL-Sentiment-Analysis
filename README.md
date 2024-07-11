# Intel Product Review Sentiment Analysis

## Overview
This project analyzes customer sentiment for five Intel products based on Amazon reviews. It uses web scraping techniques to gather data and employs natural language processing for sentiment analysis.

## Features
- Web scraping of Amazon reviews for Intel products
- Data preprocessing and cleaning
- Sentiment analysis using VADER
- Visualization of sentiment distribution

## Tools and Libraries
- Python
- Pandas: Data manipulation and analysis
- NLTK: Text preprocessing
- VADER: Sentiment analysis
- Matplotlib and Seaborn: Data visualization
- Selenium and BeautifulSoup: Web scraping

## Key Findings
- Overall positive sentiment: 73%
- Neutral sentiment: 15%
- Negative sentiment: 12%
- Product-wise sentiment analysis for I7, I3, I9, I5, and Graphic Card

## File Structure
- `intel_scraping.ipynb`: Jupyter notebook for web scraping
- `sentiment_analysis.py`: Python script for sentiment analysis
- `intell.csv`: Scraped data
- `INTEL REPORT.docx`: Detailed analysis report

## Setup and Usage
1. Install required libraries: `pip install -r requirements.txt`
2. Run the web scraping notebook: `jupyter notebook intel_scraping.ipynb`
3. Execute the sentiment analysis: `python sentiment_analysis.py`

## Results
The analysis provides insights into customer satisfaction across different Intel products, highlighting areas of strength and potential improvement.

## Future Work
- Implement more advanced NLP techniques
- Expand the dataset to include more products and reviews
- Develop a real-time sentiment analysis dashboard
