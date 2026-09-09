# AI Job Application Automation

An automated job application workflow built with **n8n** that collects job listings, tailors CV content using **Google Gemini**, generates job-specific cover letters, and tracks applications in **Google Sheets**.

## Workflow

Indeed Job Scraper → Job Processing → CV Retrieval → Gemini CV Tailoring → Cover Letter Generation → Google Docs Creation → Application Tracking

## Tech Stack

- n8n
- Google Gemini
- Apify
- Google Drive
- Google Docs API
- Google Sheets
- JavaScript
- REST APIs

## Features

- Automatically fetches job listings
- Processes jobs in batches
- Tailors existing CV content based on job descriptions
- Generates personalized cover letters
- Creates separate CV and cover-letter documents
- Stores application details and document links in Google Sheets

## Setup

1. Import `workflow.json` into n8n.
2. Configure Apify, Gemini, Google Drive, Google Docs, and Google Sheets credentials.
3. Add your CV and cover-letter template document IDs.
4. Update the job search parameters.
5. Execute or schedule the workflow.

## Note

Credentials, API keys, document IDs, and personal data are not included in this repository.
