# googlescrape
This Python-based application is designed to automate the extraction of business data from Google Maps using Playwright, a browser automation library.
It enables users to collect detailed information about businesses, such as names, addresses, contact details, reviews, and geographic coordinates, and export the data into structured formats (Excel/CSV) for further analysis.

## Key Features
Data Extraction:

Scrapes business names, addresses, websites, phone numbers, review counts, average ratings, and latitude/longitude coordinates.

Handles dynamic content loading by simulating user interactions like scrolling.

## Input Flexibility:

Accepts search queries via command-line arguments (e.g., -s "Boston dentist") or a text file (input.txt).

Supports scraping a specified number of results or all available listings.

## Automation with Playwright:

Uses headless or visible browser modes to interact with Google Maps.

Automates search execution, result navigation, and data extraction.

## Data Export:

Saves scraped data to Excel (.xlsx) and CSV files in an output folder.

Utilizes pandas for data structuring and openpyxl for Excel file generation.

## Error Handling:

Includes basic error logging to prevent crashes during scraping.

## How It Works
* Search Execution: The tool navigates to Google Maps, enters a search term, and loads all relevant business listings.
* Dynamic Scrolling: Automatically scrolls through the page to ensure all results are loaded.
* Data Collection: Clicks on each listing to extract detailed information and stores it in a structured format.
* File Export: Compiles data into a pandas DataFrame and exports it to user-friendly formats.

## Use Cases
* Market Research: Analyze competitors or identify trends in a specific location.
* Lead Generation: Collect contact details for sales outreach.
* Local SEO: Gather review data to improve business rankings.

## Requirements
* Python Environmneent  python - venv venv ----> source venv/bin/activate
* Python 3.x, Playwright, pandas, openpyxl.
* Browser binaries installed via playwright install.

## Ethical Note
This tool should be used responsibly, adhering to Google Maps' terms of service and respecting website scraping policies. Avoid aggressive scraping to prevent IP blocking.

This application simplifies bulk data collection from Google Maps, making it ideal for researchers, marketers, and developers seeking actionable insights from public business listings.



