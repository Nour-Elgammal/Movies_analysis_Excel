# Movies_analysis_Excel
Movie industry data analysis using Power Query and Pivot tables. Features a dynamic Excel dashboard for exploring historical cinema trends and ROI.
# 🎬 TMDb Movie Industry Analysis Dashboard (1960 - 2015)

## 📌 Project Overview
This project involves a comprehensive analysis of the Movie Database (TMDb), covering over 3,800 movies. The goal was to uncover trends in the film industry, identify the most profitable genres and directors, and understand the factors influencing a movie's popularity.



https://github.com/user-attachments/assets/ed65b657-2d6e-4631-95ff-c89b5e9e6916



## 🛠️ Tools & Technologies
* **Microsoft Excel:** The primary tool for data processing and visualization.
* **Power Query:** Used for advanced data cleaning, splitting columns (Directors/Cast), and handling encoding issues.
* **Power Pivot & Data Modeling:** Created relationships and calculated fields (DAX-lite) for Profit and ROI.
* **Pivot Tables & Charts:** For dynamic data summarization and visualization.

## 🧹 Data Cleaning Process
* **Handling Duplicates:** Identified and removed duplicate records to ensure data integrity.
* **Feature Engineering:** Created a `Profit` column (`Revenue_adj` - `Budget_adj`) and extracted the `Lead Actor` from the cast list.
* **Cleaning Text:** Fixed encoding issues in the `Director` column and handled missing values in `Cast` and `Director`.
* **Data Splitting:** Used Power Query to flatten the `Genres` and `Director` columns for accurate per-category analysis.

## 💡 Key Insights & Findings
* **The Profit King:** Steven Spielberg emerged as the all-time most profitable director.
* **Genre Dominance:** Adventure and Action genres consistently generate the highest revenue and popularity scores.
* **Trend Analysis:** There has been a significant surge in the popularity of Adventure films since 2010.
* **The "Epic" Factor:** Contrary to common belief, movies with a runtime between **165-194 minutes** tend to have the highest average popularity.

## 📊 Dashboard Features
* **Interactive Slicers:** Filter the entire dashboard by Year or Genre.
* **Dynamic Top 5:** Real-time update of the top genres by profit.
* **Trend Lines:** Visualizing popularity shifts over decades.

---
**Author:** Nour Elgammal  
**LinkedIn:** [Your LinkedIn Profile Link](https://www.linkedin.com/in/nour-ali-elgamal)
