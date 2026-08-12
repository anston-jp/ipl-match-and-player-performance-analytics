# IPL Match & Player Performance Analytics Dashboard

## 🌐 Overview
This project delivers a comprehensive exploratory data analysis of Indian Premier League (IPL) cricket matches spanning ten seasons (2008 to 2017). By integrating match-level metadata with ball-by-ball delivery records, the project uncovers critical insights into franchise performance, stadium utilization trends, seasonal match distributions, and elite player contributions. An interactive Excel dashboard featuring timeline and team slicers was built to facilitate dynamic stakeholder exploration.

---

## 📌 Table of Contents
- [Dataset](#-dataset)
- [Tools and Technologies Used](#-tools-and-technologies-used)
- [Business Objectives](#-business-objectives)
- [Key Findings](#-key-findings)
- [Executive Summary](#-executive-summary)
- [Recommendations](#-recommendations)
- [Limitations](#-limitations)

---

## 📂 Dataset
The analysis leverages two primary relational datasets:
1. **Matches Dataset (`matches (1).csv`):** Contains 636 match records detailing season, city, date, team matchups, toss winners, match winners, venue names, and Man of the Match awardees.
2. **Deliveries Dataset (`deliveries (1).csv`):** Contains ball-by-ball performance logs capturing batsman runs, bowler details, dismissals, and extra runs.

---

## 🛠️ Tools and Technologies Used
* **Microsoft Excel:** Data transformation, relational merging, Pivot Tables, summary aggregations, and interactive dashboard design.
* **Interactive Slicers:** Timeline slicers and team filters for real-time data slicing and customized visual reporting.

---

## 🎯 Business Objectives
The analysis addresses specific analytical questions outlined in the project brief:
1. **Total Match Volume:** How many matches were held from 2008 to 2017?
2. **Venue Utilization:** How many different venues hosted matches, and which venue hosted the least number of matches?
3. **Franchise Dominance:** Which team won the most matches and the most tosses?
4. **Seasonal Trends:** Which season hosted the highest number of matches?
5. **Top Performers:** Who are the top 10 run-scorers and the most frequent Man of the Match award winner?
6. **Interactive Interactivity:** Implementation of timeline and team slicers for dynamic filtering.

---

## 📊 Key Findings
* **Total Matches (2008–2017):** A total of **636 matches** were conducted across the 10-year period.
* **Venue Distribution:** Matches were hosted across **35 distinct venues**. The venue with the least number of hosted matches was the **OUTsurance Oval** (only 2 matches).
* **Team Dominance:** **Mumbai Indians** secured the most match victories (**92 wins**) and also won the most tosses (**85 tosses**).
* **Peak Season:** The **2013 season** hosted the highest match volume with **76 matches**.
* **Top 10 Batsmen (Run-Scorers):**
  1. SK Raina – 4,548 runs
  2. V Kohli – 4,423 runs
  3. RG Sharma – 4,207 runs
  4. G Gambhir – 4,132 runs
  5. DA Warner – 4,014 runs
  6. RV Uthappa – 3,778 runs
  7. CH Gayle – 3,651 runs
  8. S Dhawan – 3,561 runs
  9. MS Dhoni – 3,560 runs
  10. AB de Villiers – 3,486 runs
* **Man of the Match Leader:** **CH Gayle** dominated individual awards, winning the Man of the Match title a record **18 times**.

---

## 📈 Executive Summary
Over the 2008–2017 decade, the IPL established itself as a premier global sporting league, demonstrated by robust fixture density (peaking at 76 matches in 2013) and broad geographical engagement across 35 stadiums. Franchises like Mumbai Indians proved exceptionally consistent in both match execution and toss advantage. Individual brilliance was highlighted by stalwarts like Suresh Raina and Virat Kohli leading the batting charts, while explosive players like Chris Gayle captured the highest number of individual match accolades.

---

## 💡 Recommendations
* **Venue Diversification & Expansion:** While major metro stadiums receive heavy fixture allocation, exploring secondary and tertiary venues (such as emerging cricket hubs) can broaden fan reach and local economic impact.
* **Toss Strategy Analysis:** Given Mumbai Indians' high correlation between toss wins and match success, coaching and analytics staff across all franchises should re-evaluate tactical decision-making (batting vs. fielding first) based on historical venue conditions.
* **Player Retention & Brand Marketing:** Franchises should leverage historical top scorers (e.g., Virat Kohli, Rohit Sharma) and marquee match-winners (e.g., Chris Gayle) in targeted fan engagement and merchandising campaigns.

---

## ⚠️ Limitations
* **Temporal Scope:** The dataset is bounded between 2008 and 2017, omitting recent tactical evolutions, player auctions, and new franchise additions in subsequent years.
* **Data Granularity:** While ball-by-ball metrics capture scoring and dismissals, advanced situational pressures (such as pressure indices or win-probability graphs) require deeper predictive modeling beyond standard Excel Pivot Tables.

---
