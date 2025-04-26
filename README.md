# 💼 Data Job Market Demand Analysis

A **data analytics and visualization project** focused on understanding job market trends across skills, industries, locations, and experience levels. Built with **Python**, **Streamlit**, and an interactive **Power BI Dashboard** showcasing key insights and KPIs.

⚠️ This dashboard is built for **informational and research purposes**. It does not represent official employment forecasts.

---

## 📌 Project Overview

This project collects and analyzes real-world job postings using data from **public APIs**, **job boards**, and **historic datasets**.  
The goal is to **identify in-demand skills**, **growing industries**, **salary patterns**, and **geographic job opportunities**, helping users make informed career decisions.

---

## 🌟 Features

- 🛠️ **Web Scraping and API Integration** (Glassdoor, RapidAPI) + Kaggle historic data
- 📊 **Demand Analysis** for Skills, Industries, Locations, and Experience Levels
- 📈 **Power BI Dashboard** with 3 interactive pages:
  - Cover page (Summary)
  - Skill & Industry Insights
  - Location, Experience, and Salary Trends
- 🔥 **Key Performance Indicators (KPIs)** like top skills, average salaries, job demand by city
- 🌍 **Heat Maps and Correlation Charts** for deeper insights
- 🖥️ **Responsive and modern visual design**

---

## 📂 Project Structure

```bash
📦 job-market-demand-analysis/
├── Data_job.csv                # Aggregated and cleaned job postings dataset
├── PowerBI_Dashboard.pbix       # Power BI dashboard file
├── Images/
│   └── cover.png                # Cover page image for the dashboard
├── scripts/                     # (Optional) Python scripts for data collection and cleaning
│   └── clean_data.py
├── README.md                    # Project documentation (this file)
├── requirements.txt             # Python dependencies (if using scripts)
└── LICENSE                      # Open-source license file
```

---

## 🧠 Data Workflow

- **Data Sources**:
  - 📡 **RapidAPI** for real-time job listings
  - 🏢 **Glassdoor API** for company and salary insights
  - 🗃️ **Historic Kaggle Datasets** for job trends and salary benchmarks
- **Data Cleaning**: Standardized salaries, normalized job titles, handled missing fields
- **Exploratory Data Analysis (EDA)**: Skill trends, salary distribution, location analysis
- **Visualization**: Built a multi-page interactive Power BI Dashboard

---

## 📊 Visualizations

- Skill Demand Bar Charts
- Industry Growth Trends
- Salary vs Skill Correlation Graphs
- City-wise Heat Maps for Job Demand
- Experience Level Distribution Charts
- Salary Distribution Histograms

---

## 🔐 Disclaimer

This dashboard is based on **publicly available APIs and datasets** and may not represent the complete job market.  
Salary estimates and demand trends are subject to real-time changes.

---

## 🔧 Future Improvements

- ⏳ **Real-time scraping and dashboard auto-refresh**
- 🌎 **Expansion to global job markets**
- 📈 **Machine Learning models** to predict future job trends
- 🖥️ **Deployment** as a public dashboard with search filters
- 🚀 **CI/CD pipeline** for automated updates using GitHub Actions
- 🧹 **Advanced NLP techniques** for smart skill extraction

---

## ⚡ Challenges Faced

- Dealing with **API limitations** and **rate limits**
- Handling **incomplete/missing salary and experience** data
- Merging **historical and real-time data** for unified analysis
- Keeping visualizations **lightweight and highly informative**

---

## 🏁 Conclusion

This project demonstrates a full end-to-end data science pipeline, from **API integration**, **data preprocessing**, **exploratory analysis**, to **dashboard visualization**.  
It provides clear and actionable insights into the **current and emerging job market landscape**.

---

## 👨‍💻 Author
Sadnya Kolhe  

## ⭐ Credits

- **Data Sources**: RapidAPI, Glassdoor API, Kaggle Datasets
- **Tools Used**: Python, Power BI, Streamlit
- **Built with research for career development and analytics**

