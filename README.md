# 🏏 Exploratory Data Analysis of IPL Data (2008–2025)

## 📌 Overview
This project presents an **Exploratory Data Analysis (EDA)** of the Indian Premier League (IPL) dataset covering seasons from **2008 to 2025**. The goal is to understand patterns in scoring, match outcomes, venues, player composition, and overall gameplay dynamics using descriptive statistics and visual analysis.

EDA is used as a foundational step to uncover trends, detect anomalies, and identify meaningful relationships within structured cricket data.

---

## 📂 Dataset
The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/meruvakodandasuraj/ipl-complete-dataset-2008-2025-enhanced-edition

### 📊 Dataset Structure
The analysis is based on four interconnected CSV files:

- **matches.csv**  
  Contains match-level details such as teams, venue, scores, toss decisions, and results.

- **deliveries.csv**  
  Ball-by-ball dataset including runs scored, extras, wickets, and innings details.

- **players.csv**  
  Player information including roles, nationality, batting/bowling styles, and auction-related attributes.

- **seasons.csv**  
  Season-level summaries including total matches, champions, and aggregate scoring statistics.

### 📈 Dataset Size
- Matches: **1,158**
- Deliveries: **134,190**
- Players: **580**
- Seasons: **18**

---

## ⚙️ Tools & Technologies
- **Python**
- **Pandas** – data manipulation and aggregation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook**

---

## 🔍 Key Analysis Areas
- Season-wise scoring trends
- First vs second innings performance
- Venue-based scoring patterns
- Toss impact on match outcomes
- Phase-wise analysis (Powerplay, Middle overs, Death overs)
- Team performance metrics
- Player role distribution
- Auction price behavior
- Correlation between match variables

---

## 📈 Key Insights
- First-innings scores are generally higher than second-innings scores, suggesting scoreboard pressure.
- Toss decisions show **limited influence** on match outcomes.
- Venue conditions significantly affect scoring behavior.
- Strong positive correlation (**r ≈ 0.80**) exists between first and second innings scores.
- Run rates across match phases are relatively **balanced**, which challenges common T20 assumptions.
- Auction prices are highly skewed, with substantial premiums over base values.

---

## ⚠️ Limitations
- Some player and auction-related data may not be fully validated.
- External factors (weather, pitch conditions, rule changes) are not included.
- Unequal match distribution across venues may influence averages.
- Analysis is purely exploratory and does not include predictive modeling.

---

## 🚀 Future Work
- Match outcome prediction models
- Player valuation and performance forecasting
- Integration of contextual data (weather, pitch, opposition strength)
- Time-series analysis of scoring trends
- Advanced feature engineering for sports analytics

---

## 📌 Notes
This project focuses on understanding data patterns and relationships through EDA. The findings can serve as a foundation for future machine learning and predictive analytics in cricket.

---