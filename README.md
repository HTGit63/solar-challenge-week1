# 🌞 Solar Data Discovery — Week 1

This repository contains work for Week 0 of the Solar Data Discovery project under 10 Academy’s AI Mastery Program. The goal is to perform detailed exploratory data analysis (EDA) and comparison of solar radiation data for three West African countries: **Benin**, **Sierra Leone**, and **Togo**.

---

## 📊 Project Objective

Analyze and clean large-scale solar data, identify trends and anomalies, and compare the solar energy potential across countries. This work supports data-driven decision-making in renewable energy deployment.

---

## 🗂️ Repository Structure

solar-challenge-week1/
├── .github/ # GitHub Actions workflows
├── notebooks/ # Jupyter notebooks for EDA
│ ├── benin_eda.ipynb
│ ├── sierra_leone_eda.ipynb
│ ├── togo_eda.ipynb
│ └── compare_countries.ipynb
├── data/ # Cleaned CSV files
│ ├── benin_clean.csv
│ ├── sierra_leone_clean.csv
│ └── togo_clean.csv
├── src/ # (Optional) Helper Python scripts
├── requirements.txt # Python package dependencies
└── README.md # Project overview (this file)


---

## 🧪 Workflow Summary

### ✅ Task 1: Git & Environment Setup
- Repository initialized and structured
- Virtual environment and requirements.txt defined

### ✅ Task 2: EDA & Data Cleaning

- **Benin**
  - Negative irradiance values handled
  - Outliers removed using manual Z-score
  - Distributions, daily patterns, and correlation matrix plotted

- **Sierra Leone**
  - Outlier handling and exploratory plots
  - Observed lower irradiance and high humidity

- **Togo**
  - Seasonal solar trends analyzed
  - Cleaned and visualized distribution and correlation patterns

### ✅ Task 3: Cross-Country Comparison
- Boxplot comparison of GHI
- Daily GHI trends across countries
- Summary statistics (mean & median of irradiance values)
- Temperature and humidity comparison across countries

---



## 👤 Author

- Hunde Tefera — [GitHub Profile](https://github.com/HTGit63)

