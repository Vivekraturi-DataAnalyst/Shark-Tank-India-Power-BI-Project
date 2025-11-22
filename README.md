<div align="center">

<h1>🦈 Shark Tank India – Power BI Dashboard</h1>

<h2>🚀 A complete analysis of Shark Tank India (Seasons 1–4) using Power BI.</h2>

<h3>
  🔗 <a href="https://app.powerbi.com/view?r=eyJrIjoiZGI3MDkxOWUtZjQyNy00YjE1LWIyYzItZjNjNmVlMWNkOTAxIiwidCI6ImQ4MTIxYzJhLTEzMzktNDk2NC1hN2NmLWMyZjU5OTAxYzBlNiJ9" target="_blank">
  Click here to view the Live Dashboard
  </a>
</h3>

</div>

---

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

This project is an end to end Power BI dashboard analyzing all four seasons of **Shark Tank India**, created using a structured dataset sourced from Kaggle.
My goal was to explore funding patterns, investor behavior, industry performance, and founder demographics through a clean, interactive, and easy to understand report.

The dashboard includes:

* Dynamic KPIs
* Multi-page analysis
* Slicer-driven insights
* Professionally designed layouts
* Clean formatting
* DAX-powered logic for ranking, dynamic images, titles, and metrics

The dashboard is fully interactive, includes dynamic DAX calculations, clean navigation, and professional UI/UX design, making it ideal for portfolio demonstrations and analytics practice.

---

# Dataset Details

**Source:** Kaggle – Shark Tank India Dataset  

**Link:** *[Kaggle.com](https://www.kaggle.com/datasets/thirumani/shark-tank-india)*

The original dataset contained:

* Startup details
* Deal-related fields
* Sharks’ investment columns
* Pitcher demographics
* Industry information
* Multiple financial fields

However, the dataset was **not directly ready for analysis**.
Many fields were unnecessary, inconsistent, or required reshaping.
Hence, This dataset was cleaned, transformed and enhanced using:

✔ Power Query
✔ Excel
✔ DAX measures
✔ Custom logic to fix multiple problems

---

# Data Cleaning and Preparation

The raw Kaggle dataset contained 80 fields/columns and 630+ records.
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

# Dashboard Pages

My dashboard contains **four pages**, each with a specific purpose:

---

## 🟧 1) Overview

Gives a high-level snapshot of:

* Total pitches
* Total deals
* Total investment
* Avg deal amounts
* Industry distribution
* Top startups
* Top-performing sharks


<br>    

<p align="center">
  <img src="images/1.png" width="700">
</p>


---

## 🟦 2) Sharks/Investors

A complete Sharks-focused breakdown:

* Deals closed by each shark
* Total investment amount
* Shark-wise investment trends
* Industries each shark invested in
* List of startups invested by the selected shark
* **Dynamic Top 3 Podium Ranking** with shark images

  * Works perfectly with slicers and metric.

<br>    

   <p align="center">
  <img src="images/2.png" width="700">
</p>

---

## 🟩 3) Industries

A deep dive into industries:

* Industries by investment amount or deal count
* Top startups within each industry
* KPI summary for selected industries
* Season-wise trends per industry
<br>

 <p align="center">
  <img src="images/3.png" width="700">
</p> 

---

## 🟦 4) Pitchers/Founders

Insights about the pitchers:

* Gender distribution
* Age groups
* Location distribution (city & state)
* Valuation asks by founders
* Team size analysis
<br>

  <p align="center">
  <img src="images/4.png" width="700">
</p>

---

# Key Insights

Some interesting findings from the dashboard:

* Industries like Food & Beverages, Fashion, and Medical receive the highest number of investments.
* Across most seasons, Aman and Namita tend to be among the most active sharks in terms of number of deals.
* Founders aged 30-50 form the majority
* Out of 634 pitches, 360 converted into deals, showing a strong overall conversion rate of 56.78% across all seasons. 
* Maharashtra and Delhi lead in the number of pitches
* Season 2 had the highest number of total pitches
* NOOE secured the highest individual investment of ₹50M from Peyush, one of the standout deals across seasons.

---

# Tools Used

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Excel**
* **Canva & Figma** (for icons/design elements)
* **Kaggle dataset**

---

#  What I Learned

While building this project, I improved my skills in:

* ✔ Power Query data cleaning
* ✔ Unpivoting data for star-schema-like structures
* ✔ Advanced DAX (TOPN, RANKX, KEEPFILTERS, dynamic filters)
* ✔ Creating dynamic titles and dynamic images
* ✔ Fixing complex dataset issues
* ✔ Dashboard layout and UX design
* ✔ Controlling visual interactions
* ✔ Creating professional multi-page reports

---

# Conclusion

Working on this dashboard was a great learning experience that combined data cleaning, analytical thinking, and design. It allowed me to convert raw information into actionable insights while practicing real-world Power BI development.

---

# Contact

If you'd like to connect, share feedback on this project, or want to learn how I built dashboard, feel free to reach out:
**LinkedIn:** *[Vivek Raturi](www.linkedin.com/in/vivekraturi)*

---

