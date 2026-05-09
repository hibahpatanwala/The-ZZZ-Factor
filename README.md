# The ZZZ Factor: Statistical Analysis of Student Sleep Quality 💤

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)

## 📌 Project Overview
This project investigates the statistical impact of various lifestyle factors—specifically academic/non-academic screen time, daily caffeine intake, and underlying health conditions—on the sleep quality and sleep latency of university students. The objective was to execute an end-to-end data analytics workflow, from engineering custom data preprocessing pipelines to conducting rigorous statistical hypothesis testing, ultimately delivering actionable business and research insights.

## 📊 Data Pipeline & Methodology
The analysis was performed on a primary, self-reported dataset collected from a cohort of 75 students. 

* **Data Engineering:** Developed a robust Python-based preprocessing pipeline using Pandas to handle missing values, normalize complex categorical inputs (e.g., converting "HH:MM" string formats into calculable numerical hours/minutes), and structure the data for mathematical modeling.
* **Exploratory Data Analysis (EDA):** Generated data-driven visualizations using Seaborn and Matplotlib to identify initial distributions, outliers, and baseline behavioral trends.
* **Hypothesis Testing:** Applied advanced inferential statistics ($\alpha = 0.05$) to test for mathematical significance:
  * **Pearson Correlation** to quantify the linear relationship between total daily screen time and sleep latency.
  * **One-Way ANOVA** to measure the variance in overall sleep quality scores across multiple caffeine consumption brackets.
  * **Welch's Independent t-test** to compare sleep latency between students with and without reported health conditions, accounting for unequal variances.

## 💡 Key Statistical Insights
Through rigorous testing, the analysis yielded a critical, data-backed conclusion: **The Null Hypothesis Prevailed.**

* **Screen Time:** Pearson correlation testing revealed no statistically significant linear impact ($p > 0.05$) between total daily screen time and how quickly students in this sample fell asleep.
* **Caffeine Consumption:** ANOVA testing confirmed that the variance in sleep quality between individuals consuming zero caffeinated beverages versus multiple beverages was not large enough to rule out random chance.
* **Health Factors:** Self-reported health conditions did not mathematically alter the time required to fall asleep in a statistically significant manner.
* **Strategic Takeaway:** The mathematical truth of this dataset indicates that poor sleep quality within this specific student cohort is likely driven by external confounding variables not captured in the primary study (e.g., academic stress cycles, irregular sleep schedules, or environmental noise). This insight successfully pivots the research strategy toward a more targeted, secondary data collection phase.

## 🛠️ Technical Stack
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Statistical Analysis:** SciPy
* **Data Visualization:** Matplotlib, Seaborn

## 🚀 Repository Structure
* `/data`: Contains the cleaned, anonymized primary dataset used for the study (`sleep_data_cleaned.csv`).
* `/notebooks`: Contains the Jupyter notebooks detailing the data engineering pipeline and the formal hypothesis testing/EDA.
* `/reports`: Contains the final, visually formatted presentation delivered to non-technical stakeholders.

## 🤝 Acknowledgments
* Conducted as an independent statistical analysis project for data-driven academic research.
