Data Analyst Job Market in Israel
Project Goal

This project tracks Data Analyst job postings in Israel and analyzes them to understand the market while automatically evaluating how relevant each role is for me — eliminating the need to manually scroll through hundreds of postings.

What the Project Does
Automatically collects job postings every day
Extracts and structures relevant job information
Adds personalized scoring:
Job relevance score – how relevant the position is for me
Fit score – how well my profile matches the job
Enables automatic cover letter generation for selected jobs
Stores and processes data in a scalable cloud environment
Enables analysis and insights generation on the job market
Current Pipeline
Collect job postings automatically (via n8n workflows)
Extract and structure job data using AI agents
Score jobs based on relevance and personal fit
Store raw data in Google Sheets / BigQuery
Transform and normalize data using BigQuery (SQL)
Create analytics-ready tables
Visualize insights in Looker Studio
Tools
n8n (workflow orchestration)
Python (analysis & exploration)
Pandas
Jupyter Notebook
Google BigQuery (data warehouse & transformations)
Looker Studio (dashboards & visualization)
Key Questions
How many Data Analyst jobs were posted since the war started?
Which platforms publish the most positions?
What percentage of jobs am I a strong fit for?
How does demand change over time?
What experience levels are most in demand?
Data Processing & Modeling
Data is cleaned and standardized using BigQuery SQL transformations
Duplicate jobs are removed using unique job keys (Title + Company)
Location data is normalized into a consistent format
Experience requirements are categorized into structured buckets
Final datasets are optimized for analytics and dashboarding
Future Improvements
Improve AI scoring accuracy (better prompts & evaluation logic)
Add salary estimation and compensation analysis
Build a personalized job recommendation engine
Deploy a lightweight app for browsing top matches
Integrate real-time alerts for high-fit job postings
