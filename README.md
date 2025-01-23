# Companies Web Scraping Project

## Overview

A Python script that web scrapes Wikipedia to extract and save data about the largest companies in the United States by revenue.

## Prerequisites

- Python 3.x
- Required libraries:
 - `requests`
 - `beautifulsoup4`
 - `pandas`

## Installation

Install required libraries:
`pip install requests beautifulsoup4 pandas`

markdownCopy## Features

* Scrapes company data from Wikipedia
* Extracts table information about largest US companies
* Converts data to a pandas DataFrame
* Exports data to CSV file

## Usage

1. Run the script
2. Data will be scraped from Wikipedia
3. DataFrame will be created with company information
4. CSV file will be generated with the scraped data

## Data Source

* Source: Wikipedia page on largest US companies by revenue
* URL: https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue

## Notes

* Requires active internet connection
* Scraping may be subject to Wikipedia's terms of service
* Ensure you have appropriate permissions for data usage

## Potential Improvements

* Add error handling
* Implement date/timestamp for scraped data
* Create more robust data cleaning mechanisms
