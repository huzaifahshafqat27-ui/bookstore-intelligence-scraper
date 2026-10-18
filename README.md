
# Bookstore Intelligence Scraper

## Project Overview
A Python web-scraping project that collects book
titles, prices, ratings and availability from
Books to Scrape.

## Tools Used
- Python
- Requests
- BeautifulSoup
- Pandas

## Features
- Scrapes multiple catalogue pages using a loop
- Converts rating words into numeric values
- Stores the results in a Pandas DataFrame
- Exports the data to competitor_books.csv
- Supports price, rating and stock analysis

## How to Run
1. Install Python.
2. Install the required libraries:
   pip install requests beautifulsoup4 pandas
3. Run the scraper:
   python bookstore_scraper.py

## Output
competitor_books.csv

## Business Analysis
The dataset is used to identify price extremes,
average price, top-rated books and a purchasing
combination within a £100 budget.
