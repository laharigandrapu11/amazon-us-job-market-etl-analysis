# 📊 Amazon U.S. Job Market: End-to-End ETL & Data Analysis

This project provides a complete end-to-end ETL pipeline and exploratory data analysis focused on Amazon's U.S.-based job listings. It includes automated scraping, data transformation, loading, and rich visual insights into hiring trends across roles, locations, and skill requirements.

---

## 🚀 Project Goals

- Scrape job listings from [Amazon.jobs](https://www.amazon.jobs) with U.S.-only filters
- Clean and transform data (parse location, infer seniority, extract skills)
- Load into CSV/SQLite for reproducibility
- Analyze and visualize:
  - Top roles and departments
  - Most hiring cities and states
  - Role-level seniority patterns
  - In-demand tech skills
  - Optional: U.S. job heatmaps

---

## 🛠️ Tech Stack

- **Python 3**
  - `requests`, `BeautifulSoup` – Web scraping
  - `pandas`, `numpy` – Data transformation and analysis
  - `matplotlib`, `seaborn`, `plotly`, `folium` – Visualization
  - `sqlite3` – Optional structured data loading
- **Jupyter Notebook** – Interactive EDA
- **Tableau** – Interactive dashboard


