# Walmart / Target Wipes — Web Scraping

Parsing Walmart, Target, and Walgreens feminine wipes listings into clean
product tables.
Personal care category research · Google Colab / Python

## Objective
Build comparable structured product data across mass retailers: extract
detailed product information from Walmart, Target, and Walgreens wipes
listings with one parser per retailer.

## What the notebook does (`Walmart_Target_Wipes_Scraping_V4_07072026.ipynb`, 20 cells)
- Loads saved retailer HTML files from Google Drive in Colab
- **Playwright** renders pages; **BeautifulSoup** parses individual
  product tiles — one dedicated parser section each for **Walmart**,
  **Target**, and **Walgreens** feminine wipes
- Extracts name, price, and pack details into clean CSV tables

## Tools & packages
- **Playwright (async)** — browser automation / page rendering
- **BeautifulSoup (bs4)** — HTML parsing and product-tile extraction
- **pandas** — structuring and exporting the extracted data
- **urllib.parse** — URL handling
- **Google Colab** — Drive-mounted HTML files
