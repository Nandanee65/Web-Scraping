# Python Web Scraper

This project is a Python-based web scraper that collects job listings from [Indeed.com](https://in.indeed.com) using the Oxylabs API. Users can input their job search criteria, such as job title, location, and the maximum number of listings to retrieve, and the scraper saves the retrieved data into a structured CSV file for further analysis.

## Features

- User-friendly input for job search parameters (job title, location, and maximum listings).
- Fetches job data from Indeed.com, including:
  - Job title
  - Company name
  - Location
  - Job description
- Supports pagination to retrieve multiple pages of listings.
- Saves data into a CSV file with a timestamped filename.
- Utilizes Oxylabs API for proxy requests to avoid restrictions.
- Handles dynamic paths for saving files in a `scraped_csv` directory.
