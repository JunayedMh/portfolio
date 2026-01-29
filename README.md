# ⚽ English Premier League Match Predictor

## 📊 Project Overview
This project leverages **10 seasons (2016-2026)** of Premier League data to predict match outcomes (Win, Draw, Loss). Using a **Random Forest Classifier**, the model analyzes team form via rolling averages and market sentiment through bookmaker odds.

### 🧠 Mathematical Approach
- **Data Consolidation:** Aggregated 10 distinct CSV datasets into a single longitudinal master file.
- **Temporal Sorting:** Normalized date formats to ensure chronological integrity.
- **Feature Engineering:** Implemented rolling averages for key performance indicators (KPIs) like Shots on Target (HST/AST) and Goals (FTHG/FTAG).
- **Classification:** Utilized an ensemble method to mitigate variance in high-stochasticity sports data.

## 📈 Key Results
- **Validation Accuracy:** 49.53%
- **Benchmark:** Successfully outperformed the baseline random guess probability of 33.3%.

## 🛠️ Tools Used
- **Python:** Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Data Source:** [Football-Data.co.uk](http://www.football-data.co.uk/) 

## 📝 Conclusion & Future Work
While shot volume and market odds are strong predictors, future iterations will explore:
1. **Poisson Distribution:** Modeling goal frequency as a discrete probability distribution.
2. **xG Integration:** Incorporating 'Expected Goals' for higher granular accuracy.
