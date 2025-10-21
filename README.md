## Overview

This workflow automates the extraction of job listings from Manpower.fr using n8n and ScraperAPI. It handles pagination, parses key job details, and formats the output for daily delivery via Telegram or other channels.

## Features

- Scrapes multiple pages of job offers dynamically
- Parses structured data: title, location, contract type, duration, publication date, etc.
- Formats and filters results for downstream use
- Includes error handling and fan-out logic
- Ready for integration with messaging or storage systems

## Benefits

- No manual browsing or copy-paste
- Resilient to site layout changes and pagination shifts
- Easily extendable to other job boards or notification platforms

## Requirements

- n8n (self-hosted or cloud)
- ScraperAPI account with valid API key
- Telegram bot (optional)

## Notes

This workflow is not intended for production use without adaptation. It assumes basic familiarity with n8n and web scraping practices.  
Feel free to fork and customize for your own use cases.
