# Web Scraping Projects: Company Revenues & Flight Ticket Prices

This repository contains two independent Python web scraping projects:

1. Scraping the **List of Largest U.S. Companies by Revenue** from Wikipedia using **Beautiful Soup**.
2. Scraping **Flight Ticket Prices** from a flight booking website to analyse travel costs.

Both projects demonstrate fundamental web scraping techniques using `requests`, `BeautifulSoup`, and optional data storage with `pandas`.

---

## Project Structure

```
Webscraping_projects_using_beautifulSoup/
│
├── flight_scraping.ipynb
│
├── Wikipedia_site_scraping.ipynb
│
└── README.md
```

---

## Technologies Used

* **Python 3.11.4**
* **BeautifulSoup (bs4)**
* **Requests**
* **Pandas** (optional, for tabular data handling)
* **Jupyter Notebook** (optional, for testing and visualization)

---

## 1⃣ Project: Largest U.S. Companies by Revenue

### Objective

To extract a structured list of the largest companies in the United States by revenue, as listed on Wikipedia. The goal is to clean, organize, and optionally export the data for further analysis.

### Source

> Wikipedia page: [List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

### What It Does

* Sends a `GET` request to the Wikipedia page.
* Parses the HTML using Beautiful Soup.
* Locates the main revenue table (usually the first or second table on the page).
* Extracts the table headers and rows.
* Cleans up the text (removes newline characters, extra spaces, and footnotes).
* Stores the data in a structured pandas DataFrame.
* Optionally exports to CSV or Excel.

---

## 2⃣ Project: Flight Ticket Price Scraper

### Description

This project is a simple Python-based web scraper that extracts flight prices from a flight booking website using **BeautifulSoup**. It was designed to gather flight price data based on origin-destination pairs, providing insights into pricing trends and availability.


## Features

- Scrapes flight prices for routes from multiple origins to destinations.
- Parses and extracts relevant data using `BeautifulSoup`.
- Saves data in a structured format (CSV/JSON).
- Easy to extend for different flight websites (depending on their HTML structure).

## Technologies Used

- Python
- BeautifulSoup
- Requests
- Pandas (optional, for data handling)
- CSV (for data output)
