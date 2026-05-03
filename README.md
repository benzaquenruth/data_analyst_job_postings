# Data Analyst Job Market in Israel

## 🎯 Project Goal
Track Data Analyst job postings in Israel and analyze the market while automatically evaluating how relevant each role is for me — eliminating the need to manually scroll through hundreds of postings.

<img width="1774" height="887" alt="ed0867ed-18c8-4dc5-a571-23cc46410e46" src="https://github.com/user-attachments/assets/739933ce-a5fe-4bc3-ac35-7c532e0f309c" />


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
