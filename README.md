# 🏆 2026 World Cup Final Prediction: Spain vs Argentina

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-8CAAE6)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

This repository contains a Data Science and Machine Learning approach to predicting the outcome of the 2026 World Cup Final between Spain and Argentina. 

The prediction relies on a **Hybrid Model** that combines the **Poisson Distribution (Expected Goals)** and the **Elo Rating System**, providing a balanced analysis of both recent attacking/defensive forms and historical pedigree.

## 📊 Methodology

The analysis uses a weighted blend of two popular sports analytics models:
1. **Poisson Distribution (60% Weight):** Focuses on a 5-year rolling window (2021-2026) to calculate Expected Goals ($\lambda$) based on Attack and Defense strengths. 
2. **Elo Rating System (40% Weight):** Calculates long-term historical strength by updating points continuously from the oldest available match data.

*Assumption: The final is played at a neutral venue, meaning no home advantage is applied.*

## 📂 Dataset
The dataset utilized is the **International Football Results from 1872 to 2017 (Updated to 2026)** sourced from Kaggle. It contains over 49,000 international football matches. 

## 🚀 Results & Insights

Based on 5,233 matches over the last 5 years:
* **Spain:** Highly aggressive, averaging 2.35 goals scored per match.
* **Argentina:** An impenetrable defense, conceding only 0.45 goals per match.

**Final Blended Probability:**
* 🇦🇷 **Argentina Win:** 43.2%
* ⚖️ **Draw (Extra Time):** 27.8%
* 🇪🇸 **Spain Win:** 29.0%

Statistically, Argentina enters the match as the slight favorite, driven heavily by their phenomenal defensive metrics. The most likely scoreline in normal time is 0-1 for Argentina or a 0-0 draw.

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/username/wc2026-final-prediction-hybrid.git](https://github.com/username/wc2026-final-prediction-hybrid.git)
