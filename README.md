# Complaints to Action

A browser-based demo for reporting, tracking, and reviewing civic complaints.

## Features
- Complaint form with category and priority analysis
- Schematic fictional city map
- Complaint tracking and admin dashboard
- Fictional sample complaint data

## Important demo limitations
- This is a frontend demo. Complaints are stored in the current browser's local storage only.
- It does not include a server-side database or external AI model.
- The city and sample records are fictional.

## Run locally
Open `index.html` in a modern browser.

## Deploy to Google Cloud Run
This repository includes a Dockerfile that serves the static page with Nginx on port 8080. Connect the GitHub repository to Cloud Run or build and deploy it using Google Cloud's deployment flow.
