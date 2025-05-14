# 📊 Remote Job Market Insights for Financial Analysts

## 🛠 Tech Stack

**Languages & Tools Used:**

- Python
- SQL
- PostgreSQL (AWS RDS)
- SQLAlchemy
- Pandas
- Jupyter Notebooks
- Matplotlib / Seaborn
- GitHub & GitHub Actions

---

## 🎯 Project Objective

**Who are you helping?**  
Job seekers and financial data analysts who want to understand remote job trends.

**What problem are you solving?**  
Identifying salary insights and top hiring companies for remote jobs for financial analysts using structured and semi-structured data.

**How will you solve their problem?**  
By cleaning, analyzing, and visualizing job listings from remote job APIs and Indeed, with aggregated insights into salary, company, and job roles.

---

## 💼 Job Description

This project aligns with a data analyst role posted by a tech-driven HR company focused on job market intelligence. The role emphasized data pipeline design, SQL, data storytelling, and dashboard development.

**Relation to the Project:**  
This analysis simulates a real-world workflow using SQL, Jupyter Notebooks, and data visualization, showcasing how to extract actionable insights from job listing datasets.

[📄 View Job Description (PDF)](proposal/Job%20Description.pdf)

---

## 📂 Data

**Sources:**
- Remote Job API (public job data)
- Web-scraped Indeed job listings

**Links:**
- [Jobicy API]("https://jobicy.com/api/v2/remote-jobs?count=5&geo=usa&industry=accounting-finance")
- [Indeed (scraped)](https://www.indeed.com)

**Characteristics:**
- `remote_jobs`: Includes job level, salary range, title, and company info
- `indeed_jobs`: Includes job title, salary (as string), and company+location

---

## 📓 Notebooks & Scripts

- [`Jobicy API Analytics Queries Notebook`](notebooks/JOBICY_API_SQL_Analysis.ipynb):  
- [`Indeed Job Scraper Analytics Queries Notebook`](notebooks/INDEED_Web_Scrape_SQL_Analysis.ipynb):  
  Main notebook performing SQL queries (CTEs, JOINs, Window functions) and extracting visual insights from both job datasets.

- [`Visualizations.pdf`](reports/Visualizations.pdf):  
  PDF dashboard with salary and job role insights for stakeholders.

---

## 🔮 Future Improvements

- Integrate real-time job API calls with automatic refresh in notebooks using scheduled GitHub Actions or Airflow.
- Expand analysis by adding additional job boards (e.g., LinkedIn, Glassdoor) to improve coverage and model salary predictions.
