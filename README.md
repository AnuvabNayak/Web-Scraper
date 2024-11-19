# Web-Scraper
This project is a Python-based web scraper that extracts data from URL. The script collects essential information, such as company name, website, phone number, and address, and stores it in a CSV file for further use.

**Features**
- Scrapes company information including:
1. Name
2. Website
3. Phone number
4. Address
5. Category (predefined as "Digital Marketing Agencies")
6. Description (placeholder)
7. Email (placeholder)

- Supports pagination to scrape multiple pages.
- Stops scraping after collecting details of 50 companies or if no more companies are found.
- Outputs the data into a CSV file

**Requirements**
Ensure you have Python 3 installed along with the following dependencies:

1. requests: For making HTTP requests.
2. beautifulsoup4: For parsing HTML content.
3. pandas: For organizing and exporting data.
