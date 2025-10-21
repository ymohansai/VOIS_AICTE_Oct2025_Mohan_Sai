# 🎬 Netflix Content Trends Analysis

## 📘 Project Overview
This project analyzes the **Netflix dataset (2008–2021)** to understand how Netflix’s content library has evolved over the years.  
It explores patterns in **Movies vs TV Shows**, **genres**, and **country contributions**, helping identify strategic insights for future content decisions.

---

## 🎯 Problem Statement
With growing competition from platforms like **Amazon Prime Video** and **Disney+**, Netflix must strategically analyze its content catalog to understand:
- The **balance between Movies and TV Shows**
- The **popularity of genres** over time
- The **contribution of different countries** to Netflix’s library

The goal is to perform a **Content Trends Analysis for Strategic Recommendations** — uncovering how Netflix’s catalog has changed and which content types drive engagement and diversity.

---

## 📂 Dataset Information
- **Dataset Name:** Netflix Dataset  
- **Records:** 7,789  
- **Columns:** 11  
- **Time Span:** 2008–2021  
- **Key Attributes:**
  - `Show_Id`: Unique ID for each title  
  - `Category` / `Type`: Movie or TV Show  
  - `Title`: Title of the content  
  - `Director`, `Cast`, `Country`, `Release_Date`  
  - `Rating`: Content rating (e.g., TV-MA, PG-13)  
  - `Duration`: Movie duration or TV Show seasons  
  - `Description`: Short overview of the content

---

## 🧠 Objectives
1. Analyze the **distribution of Movies vs TV Shows** over the years.  
2. Identify the **most common genres** and their **popularity trends**.  
3. Examine **country-wise contributions** to Netflix’s catalog.  
4. Provide **strategic insights** for future content planning.

---

## ⚙️ Technologies Used
- **Python 3.11+**
- **Jupyter Notebook**
- **Libraries:**  
  - `pandas` → Data cleaning & manipulation  
  - `matplotlib` → Visualizations  
  - `numpy` → Numerical operations  

---

## 📊 Steps in Analysis
1. **Data Loading & Inspection**  
   - Loaded dataset using pandas  
   - Checked missing values and column data types  

2. **Data Cleaning & Transformation**  
   - Parsed `Release_Date` to extract `year`  
   - Standardized column names (`Category` → `type`)  
   - Created a `genres` column from `Type` or `listed_in`  

3. **Exploratory Data Analysis (EDA)**  
   - Count of **Movies vs TV Shows (overall)**  
   - Trend of **titles released per year**  
   - **Top 12 genres**  
   - **Top 12 contributing countries**

4. **Insights & Recommendations**  
   - Visualized how content evolved over time  
   - Highlighted leading genres and countries  
   - Suggested data-driven strategies for Netflix’s content mix

---

## 📈 Key Findings
- **Movies dominate** the catalog but TV Shows are steadily increasing post-2015.  
- **Top genres** include *International Movies*, *Dramas*, and *Comedies*.  
- **United States**, *India*, and *United Kingdom* contribute the most content.  
- The platform has become **increasingly global**, with growing representation from Asian countries.

---

## 💡 Strategic Recommendations
- Invest more in **TV Shows and Originals**, which show strong upward trends.  
- Focus on **emerging markets** (India, Korea, Japan) for future growth.  
- Expand underrepresented but promising genres (e.g., **Documentaries**, **Thrillers**).  
- Maintain diversity by producing localized content across regions.

---

## 📚 Expected Outcomes
- A clear view of how Netflix’s content strategy evolved.  
- Identification of top-performing genres and countries.  
- Actionable insights for **strategic decision-making** in content acquisition and production.

---

## 🧩 Files in This Project
| File | Description |
|------|--------------|
| `Netflix_Content_Trends_Analysis.ipynb` | Main analysis notebook |
| `Netflix Dataset.csv` | Raw dataset |
| `netflix_clean_sample.csv` | Cleaned dataset used in analysis |
| `plot_type_count.png` | Movies vs TV Shows chart |
| `plot_titles_by_year.png` | Titles trend over the years |
| `plot_top_genres.png` | Top genres chart |
| `plot_top_countries.png` | Top countries chart |
| `README.md` | Project documentation (this file) |

---

## 🚀 Future Scope
- Add **genre trends over time** visualization.  
- Perform **sentiment analysis** on user reviews (if available).  
- Explore **rating patterns** and **content duration** distribution.  
- Use **machine learning** to predict popular genres or future hits.

---
