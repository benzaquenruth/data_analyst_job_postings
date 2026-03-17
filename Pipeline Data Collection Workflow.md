## Pipeline Data Collection Workflow
Here we also collect the data, but also do the ratings and the cover letters. Everything is automatize :)

tools: 8n8

<img width="1081" height="463" alt="Screenshot 2026-03-17 115448" src="https://github.com/user-attachments/assets/1f3a4e4f-0f63-405f-80fd-d418a94f5102" />

## Workflow

### Trigger
Every morning at the same hour, the workflow is automatically triggered and starts the data collection process.

### Actors
The workflow uses the **Apify platform**.  
It activates actors on this platform. An *actor* is essentially a web scraper that collects job postings.  
The scraper gathers all job posts published in the **last 24 hours** from the target platforms.

### OpenAI Agent
This is a key part of the pipeline.

The OpenAI agent:
- organizes the scraped information into structured fields
- extracts important attributes from each job post
- generates two important fields:
  - **Rating** – how relevant the position is for my job search
  - **Fit for the job** – how well my profile matches the job requirements

### Google Sheets
All processed fields are then stored in **Google Sheets**, where each row represents a job posting with its structured attributes and scores.
