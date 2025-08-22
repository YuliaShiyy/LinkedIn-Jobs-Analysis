# LinkedIn Jobs Analysis

This repository contains **data cleaning, analysis, and visualization** of LinkedIn job postings in Sweden.  
It is part of the broader [LinkedIn Jobs Pipeline Project](https://github.com/yuliashiyy/linkedin-jobs-pipeline).

---

## 📊 Features
- **Data Cleaning**
  - Deduplication by `job_id`
  - Extract city, work mode, applications, and skills
- **Exploratory Analysis**
  - Job distribution by city and company
  - Application distribution and competitiveness metric
- **Skills Demand**
  - Top 20 most frequent skills
  - Skills word cloud visualization
- **Competitiveness Metric**
  - Defined as:  
    \[
    Competitiveness = \frac{Applications}{Days Posted + 1}
    \]
  - Median competitiveness and distribution analysis

---

## 📂 Project Structure
    linkedin-jobs-analysis/
    │
    ├── data/
    │ ├── linkedin_jobs_sample.csv
    │ └── linkedin_jobs_cleaned_with_skills.csv
    │
    ├── notebooks/
    │ └── analysis.ipynb
    │
    ├── visualizations/
    │ ├── top10_cities.png
    │ ├── top10_companies.png
    │ ├── applications_distribution.png
    │ ├── competitiveness_distribution.png
    │ ├── top20_skills.png
    │ └── skills_wordcloud.png
    │
    ├── report/
    │ └── linkedin_jobs_analysis.docx
    │
    ├── requirements.txt
    └── README.md

---

## ⚙️ Requirements
See `requirements.txt` for full dependencies:
pandas
matplotlib
wordcloud


---

## 🚀 Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/yuliashiyy/linkedin-jobs-analysis.git

2. Install requirements:
   ```bash
    pip install -r requirements.txt

3. Open the notebook:
   ```bash
    jupyter notebook notebooks/analysis.ipynb

📌 Related Repositories

- [LinkedIn Jobs Scraper](https://github.com/yuliashiyy/linkedin-jobs-scraper)  
- [LinkedIn Jobs Pipeline](https://github.com/yuliashiyy/linkedin-jobs-pipeline)  
