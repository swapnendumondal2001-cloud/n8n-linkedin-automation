# n8n LinkedIn Post Automation

## Overview
This project automates LinkedIn post scraping using n8n, processes the data, and stores results in Google Sheets.

## Workflow Features
- LinkedIn post scraping via API
- Batch processing with retries
- Status polling and wait nodes
- Google Sheets integration

## Tech Stack
- n8n
- Google Sheets API
- LinkedIn scraping API

## Setup Instructions
1. Install n8n
2. Import workflow JSON from `/workflows`
3. Configure credentials:
   - Google Sheets OAuth2
   - LinkedIn API / Scraper API
4. Set environment variables (see `.env.example`)
5. Execute workflow


## Notes
- No credentials or secrets are included.
- OAuth must be configured by the user.

## Author
Swapnendu Mondal
