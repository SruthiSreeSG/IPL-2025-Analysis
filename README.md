# 🏏 IPL Data Analysis with Python

This project involves detailed data analysis of IPL matches using Python. It focuses on uncovering performance patterns, venue trends, and key player metrics (batting and bowling) to turn cricket statistics into data-driven stories.

---

## 🔍 Problem Statement

The Indian Premier League (IPL) is rich with data across seasons, yet raw stats alone don’t reveal actionable insights. The objective of this project is to analyze:
- Player performance patterns (batting/bowling)
- Venue trends and scoring behavior
- Match conditions and outcomes

We explore **how teams, venues, and individual players contribute to game dynamics** using EDA techniques.

---

## 📊 Key Areas of Analysis

### 🏟️ 1. Venue Analysis
- Total runs scored and matches played per venue
- Count of wickets per venue and type
- Extras given (wides, no-balls, leg byes, etc.)
- Merged insights into a comprehensive **venue performance table**

📁 Output: `Venue_data.csv`

---

### 👨‍🏏 2. Striker (Batsman) Analysis
- Total runs, innings, strike rate, average, dismissal count
- Milestones: 4s, 6s, 50s, 100s
- Team association and number of not outs
- Derived a **comprehensive batsman performance table**

📁 Output: `Striker_Table.csv`

---

### 👨‍🎯 3. Bowler Analysis
- Overs bowled, runs conceded, economy rate
- Match-wise bowling figures
- 4-wicket and 5-wicket hauls
- Best bowling performance in a match
- Final compiled **bowler summary table**

📁 Output: `Bowler_Table.csv`

---

## 🧠 Approach

### 🧾  Tools & Technologies
- 🐍**Python**: pandas, numpy, matplotlib, seaborn
- 📋**Jupyter Notebook**: EDA scripting
- 📁**CSV Files**: IPL `deliveries.csv`
- 🧼 Data cleaning and transformation
  
### Key Techniques
- Feature engineering (venue extraction, date-time conversion)
- GroupBy aggregation and multi-index merging
- Filtering legal deliveries and dismissal types
- Case-wise logic for match performance metrics
- Merging dataframes for final summary charts

---


