# Data Analyst Job Market in Israel

## 🎯 Project Goal
Track Data Analyst job postings in Israel and analyze the market while automatically evaluating how relevant each role is for me — eliminating the need to manually scroll through hundreds of postings.


<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/21f3b217-57fe-4899-820f-935d993d0468" />

---

## ⚙️ What the Project Does
- Collects job postings automatically on a daily basis  (from Indeed and LinkedIn)
- Extracts and structures relevant job information  
- Adds personalized scoring:
  - **Job relevance score** – how relevant the position is for me  
  - **Fit score** – how well my profile matches the job  
- Generates **cover letters automatically** for selected jobs  
- Stores and processes data in a scalable cloud environment  
- Enables data analysis and insight generation  

---

## 🔄 Current Pipeline
1. Collect job postings automatically (n8n workflows)  
2. Extract and structure job data using AI agents  
3. Score jobs based on relevance and personal fit  
4. Store raw data in **Google Sheets / BigQuery**  
5. Transform and normalize data using **BigQuery (SQL)**  
6. Create analytics-ready tables  
7. Build dashboards in **Looker Studio**  

---

## 🛠️ Tech Stack
- **n8n** – workflow orchestration  
- **Python** – analysis & exploration  
- **Pandas**  
- **Jupyter Notebook**  
- **Google BigQuery** – data warehouse & transformations  
- **Looker Studio** – dashboards & visualization  

---

## ❓ Key Questions
- How many Data Analyst jobs were posted? Weekly? Montly?  
- Which platforms publish the most positions?  
- What percentage of jobs am I a **strong fit** for?  
- How does demand change over time?  
- What experience levels are most in demand?  

---

## 🧹 Data Processing & Modeling
- Data is cleaned and standardized using **BigQuery SQL transformations**  
- Duplicate jobs are removed using a unique key (**Title + Company**)  
- Location data is normalized into a consistent format  
- Experience requirements are categorized into structured buckets  
- Final datasets are optimized for analytics and dashboarding  

---

## 🚀 Future Improvements
- Improve AI scoring accuracy (better prompts & evaluation logic)  
- Add salary estimation and compensation analysis  
- Build a personalized job recommendation engine  
- Develop a lightweight app for browsing top matches  
- Add real-time alerts for high-fit job postings  

---


## 📁 Repository Structure

This repository includes all the main components used to build and analyze the job market pipeline:

### 🔄 8n8 Data Collection Workflow
**File:** `8n8 Data Collection Workflow.md`  
Contains a visual and explanation of the n8n workflow used to automatically collect job postings.  
This is the **data ingestion layer** of the project — responsible for scraping, initial processing, and feeding the pipeline.


### 📊 Initial Dataset
**File:** `Job Listings Database.xlsx`  
A sample of the first job postings collected at the beginning of the project.  
- Represents the **raw structure of the data before improvements**  
- Useful for understanding how the data originally looked  
- The current pipeline includes additional enhancements and better structuring  


### 🔍 Exploratory Data Analysis (EDA)
**File:** `01_job_market_eda.ipynb`  
Jupyter Notebook used for the **initial exploration of the dataset**.

Includes:
- Data cleaning and preprocessing  
- First-level analysis and aggregations  
- Identification of data quality issues  
- Early insights and visualizations  

This step was critical to:
- Understand the dataset  
- Define normalization and transformation logic in BigQuery  
- Improve the data collection process in n8n  
- Build a more structured and scalable pipeline  


