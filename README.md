# 📊 Website Traffic & Engagement Analysis

## 🔍 Project Overview
This project analyzes website traffic and user engagement data using Python.
The goal is to understand how users interact with a website across different
marketing channels and time periods — helping businesses make smarter
decisions about where to focus their efforts.

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas** – Data cleaning & manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical charts & heatmaps
- **Google Colab** – Development environment

---

## 📁 Dataset
- **Source:** Google Analytics data export (CSV)
- **Key Columns:**
  - `Channel Group` – Traffic source (Organic, Direct, Referral, etc.)
  - `DateHour` – Timestamp of sessions
  - `Users` – Number of users
  - `Sessions` – Total sessions
  - `Engaged Sessions` – Sessions with meaningful interaction
  - `Engagement Rate` – Ratio of engaged sessions
  - `Average Engagement Time per Session`
  - `Events per Session`, `Event Count`

---

## 📌 Key Analysis Performed

| # | Analysis | Chart Type |
|---|----------|------------|
| 1 | Sessions and Users Over Time | Line Chart |
| 2 | Total Users by Channel | Bar Chart |
| 3 | Average Engagement Time by Channel | Bar Chart |
| 4 | Engagement Rate Distribution by Channel | Box Plot |
| 5 | Engaged vs Non-Engaged Sessions | Grouped Bar Chart |
| 6 | Traffic by Hour and Channel | Heatmap |
| 7 | Engagement Rate vs Sessions Over Time | Dual Line Chart |

---

## 💡 Key Insights
- Identified which **marketing channels** bring the most users and engaged sessions
- Found **peak traffic hours** using heatmap analysis
- Compared **engaged vs non-engaged sessions** across all channels
- Tracked how **engagement rate changes over time** relative to session volume
- Highlighted channels with **highest average engagement time**

---

## 🧹 Data Cleaning Steps
- Renamed and restructured column headers from raw Google Analytics export
- Converted `DateHour` to proper datetime format (`%Y%m%d%H`)
- Extracted `Hour` feature from datetime for time-based analysis
- Converted all metric columns to numeric data types

---

## 📂 Project Structure
```
website-analysis/
│
├── Website_Analysis.ipynb   # Main Jupyter Notebook
├── data-export.csv          # Raw dataset (Google Analytics export)
└── README.md                # Project documentation
```

---

## 🚀 How to Run
1. Clone this repository
2. Open `Website_Analysis.ipynb` in Google Colab or Jupyter Notebook
3. Upload your Google Analytics CSV file when prompted
4. Run all cells

---

## 👩‍💻 Author
**Yaminee Rahangdale**  
MCA Student | Aspiring Data Analyst  
📧 yamineerahangdale1@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/your-linkedin-here)
