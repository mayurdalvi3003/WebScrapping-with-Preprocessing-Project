# Web Scraping and Data Preprocessing Project

## Project Overview

This project involves web scraping baggage allowance information from the Qatar Airways website (https://www.qatarairways.com/en/baggage/allowance.html) using Selenium and BeautifulSoup, and preprocessing the data using Python pandas. The final output includes multiple cleaned datasets saved as CSV and JSON files for different classes of baggage allowance.

## Features

### 1. Web Scraping:

- Uses Selenium to handle dynamic content loading.

- Extracts HTML content after JavaScript-rendered tables are fully loaded.

- Parses HTML content using BeautifulSoup to locate and extract tables.

### 2. Data Preprocessing:

- Cleans and standardizes data for better usability.

- Handles missing data and ensures consistent formatting.

- Creates structured JSON outputs for each baggage class.

### 3. Output Files:

- Table 1: table_1_data.csv

- Table 2: table_2_data.csv

- Table 3: table_3_data.csv

- Table 4: table_4_data.csv

- Preprocessed Economy Class: Economy_Class_Updated.json

- Preprocessed Business Class: Business_Class_Updated.json

- Preprocessed First Class: First_Class_Updated.json

## File Structure

### Code Files

- scraper.py: Contains the web scraping logic using Selenium and BeautifulSoup.

- preprocessing.py: Handles the cleaning and preprocessing of extracted data.

### Output Files

### 1. Raw CSVs:

- table_1_data.csv

- table_2_data.csv

- table_3_data.csv

- table_4_data.csv

### 2. Processed JSONs:

- Economy_Class_Updated.json

- Business_Class_Updated.json

- First_Class_Updated.json

## Workflow

### 1.Setup:

- Install required Python libraries:

`pip install pandas selenium beautifulsoup4 webdriver-manager`

### 2.Web Scraping:

- Execute `Web Scrapping Code.py` to scrape and save data tables as raw CSV files.

### 3.Preprocessing:

- Run `Web Scrapping Preprocessing by mayur.ipynb` to clean and transform raw CSVs into structured JSON files.

## Example Usage

### Running the Scraper

- python `Web Scrapping Code.py`

This saves the scraped tables as table_1_data.csv, table_2_data.csv, etc.

### Running the Preprocessing

- python `Web Scrapping Preprocessing by mayur.ipynb`

This generates structured JSON files for economy, business, and first-class baggage allowances.

## Requirements

- Python 3.8+

- Google Chrome (latest version)

- ChromeDriver (managed automatically by webdriver-manager)

## Highlights

- The project efficiently scrapes dynamic web content and converts it into useful data formats.

- Preprocessed datasets are ready for further analysis or integration with other systems
## Welcome to our project 
Thank you for your interest in contributing!

We value collaboration and welcome developers of all levels to help improve this project.

Check the contribution guide to get started.
Explore open issues to find tasks you’d like to work on.
Let’s build something great together.
