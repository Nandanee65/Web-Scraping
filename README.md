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

## Requirements

- Python 3.8 or higher
- Libraries specified in `requirements.txt`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/NuZard84/python-web-scraper.git
   cd python-web-scraper
   pip install -r requirements.txt
   ```

2. Make .env file:

   ```bash
   OXILAB_USERNAME=your_username
   OXILAB_PASSWORD=your_password
   ```

3. Run the code:
   ```bash
   cd main
   python beutiful.py
   ```

### Instructions:

1. Save this as `README.md` in your project's root directory.
2. Replace `https://github.com/NuZard84/python-web-scraper.git` with the actual URL of your repository.
3. Add or update the `LICENSE` file in your project if applicable.
