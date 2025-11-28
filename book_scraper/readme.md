
# 📚 BooksToScrape Web Scraper

A **simple Python scraper** that collects book data from [BooksToScrape](https://books.toscrape.com/) and saves it to a CSV file. Perfect for learning web scraping or adding a practical project to your GitHub portfolio.

---

## Features

- Scrapes multiple pages of BooksToScrape.  
- Extracts the following data for each book:
  - Title  
  - Price  
  - Availability  
  - Rating   
- Saves data to a **CSV file** with proper UTF-8 encoding.  
- Polite scraping with random delays.  
- Fully function-based and easy to run.  

---

## Requirements

- Python 3.x  
- `requests`  
- `beautifulsoup4`
- `lxml`  

Install dependencies via pip:

```bash
pip install requests beautifulsoup4 lxml
