# Web Scraper Toolkit

A powerful Python web scraping framework with built-in proxy rotation, rate limiting, and data export.

## Features

- Multi-target scraping with configurable selectors
- Automatic proxy rotation and IP management
- Anti-detection with randomized headers and delays
- Export data to CSV, JSON, and SQLite
- Built-in retry logic and error handling
- Selenium support for JavaScript-heavy pages

## Tech Stack

- Python 3.11+
- BeautifulSoup4 and Scrapy
- Selenium WebDriver
- Requests with retry adapters
- Pandas for data processing

## Quick Start

```
pip install -r requirements.txt
python scraper.py --target example.com --output data.csv
```

## License

MIT License
