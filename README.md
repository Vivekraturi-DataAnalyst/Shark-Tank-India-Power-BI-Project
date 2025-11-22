# 🦈 Shark Tank India – Power BI Dashboard

A complete analysis of Shark Tank India (Seasons 1–4) using Power BI.

---

# 📑 Table of Contents

* [Project Overview](#project-overview)
* [Dataset Details](#dataset-details)
* [Data Cleaning and Preparation](#data-cleaning-and-preparation)
* [Dashboard Pages](#dashboard-pages)
* [Key Insights](#key-insights)
* [Tools Used](#tools-used)
* [What I Learned](#what-i-learned)
* [How to Use This Project](#how-to-use-this-project)
* [Contact](#contact)

---

# Project Overview

I created this Power BI dashboard to analyze **4 seasons of Shark Tank India** using a dataset from Kaggle.
My main objective was to study funding trends, investor behavior, industry performance, and founder demographics in a clean, interactive, and user-friendly dashboard.

The project includes:

* Dynamic KPIs
* Multi-page analysis
* Slicer-driven insights
* Professional navigation
* Clean formatting
* DAX-powered logic for ranking, dynamic images, titles, and metrics

🔗 **Live Dashboard Link:** *Paste your public Power BI link here*

---

# Dataset Details

**Source:** Kaggle – Shark Tank India (Season 1–4) Dataset
**Link:** *Paste Kaggle link here*

The original dataset contained:

* Startup details
* Deal-related fields
* Sharks’ investment columns
* Pitcher demographics
* Industry information
* Multiple financial fields

However, the dataset was **not directly ready for analysis**.
Many fields were unnecessary, inconsistent, or required reshaping.

---

# 🧼 Data Cleaning and Preparation

I spent a good amount of time preparing the dataset to make it suitable for a clean Power BI dashboard.

### ✔ Key cleaning steps I performed:

* Removed **unwanted and irrelevant fields**
* Standardized **industry names, states, cities**
* Fixed **multiple rows per pitch issue** (same pitch spread across multiple rows)
* Used Power Query to **unpivot shark investment fields**
* Created a **shark-invested list column**
* Removed **duplicate entries**
* Converted financial columns to the correct data types
* Cleaned and categorized age groups
* Added gender categories (Male / Female / Mixed / Trans)
* Replaced blank values with proper nulls
* Ensured accurate **distinct pitch-level calculations**
* Cleaned deal-related fields to avoid inflated sums
* Fixed the “blank shark” deal problem
* Added extra helper tables (Metric Selector, Podium Table) for dynamic visuals
* Ensured smooth slicer interactions across pages

After cleaning, I prepared a structured version of the dataset suitable for multi-page reporting.

---

# 📊 Dashboard Pages

My dashboard contains **four pages**, each with a specific purpose:

---

## 🟧 1) Overview

A high-level summary of:

* Total pitches
* Total deals
* Total investment
* Avg deal amounts
* Industry distribution
* Funding trend across seasons
* Top-performing sharks

---

## 🟦 2) Investors

A complete investor-focused breakdown:

* Deals closed by each shark
* Total investment amount
* Shark-wise investment trends
* Industries each shark invested in
* List of startups invested by the selected shark
* **Dynamic Top 3 Podium Ranking** with shark images

  * Works perfectly with slicers and metric selector

---

## 🟩 3) Industries

A deep dive into industry behavior:

* Industries by investment amount or deal count
* Top startups within each industry
* KPI summary for selected industries
* Dynamic chart titles based on slicers
* Season-wise trends per industry

---

## 🟦 4) Founders

Insights about the pitchers:

* Gender categories
* Age groups
* Location distribution (city & state)
* Revenue and sales patterns
* Deal conversion rates
* Team size analysis

---

# 📈 Key Insights

Some interesting findings from the dashboard:

* F&B, Fashion, and Tech dominate the startup pitches
* Certain sharks prefer small frequent deals while others invest larger amounts in fewer startups
* Founders aged 25–35 form the majority
* Solo founders have lower deal conversion than team founders
* Delhi and Maharashtra lead in the number of pitches
* Season 1 had the highest number of total pitches
* Some industries have much better conversion rates than others

---

# 🛠 Tools Used

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Excel**
* **Canva** (for icons/design elements)
* **Kaggle dataset**

---

# 🎓 What I Learned

While building this project, I improved my skills in:

* Power Query data cleaning
* Unpivoting data for star-schema-like structures
* Writing advanced DAX
* Creating dynamic titles and dynamic images
* Fixing complex multiple-row pitch issues
* Dashboard layout and user experience design
* Publishing dashboards to Power BI Service
* Controlling visual interactions
* Creating professional multi-page reports

---

# 📂 How to Use This Project

1. Download the PBIX file
2. Open it in the latest version of Power BI Desktop
3. All slicers, filters, and dynamic visuals will work automatically
4. No paid visuals were used — everything uses Power BI native visuals

---

# 📞 Contact

If you want the PBIX file, want guidance on building dashboards, or want to connect, feel free to reach out:

**LinkedIn:** *Paste your LinkedIn URL here*

---

