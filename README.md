# Homicide Data Analysis (Python & R Lab Project)

This project was developed as part of the *Python and R for Data Science Lab* at LUISS Guido Carli (2023–2024). The analysis focuses on U.S. homicide data with particular attention to demographic and geographic trends in states like Texas and California.

We implemented various data cleaning, processing, and visualization techniques to uncover patterns in homicide incidents, resolution rates, and population-related dynamics.

---

## 🎯 Objectives

- Identify trends in homicide incidents over time
- Analyze demographic attributes of victims and perpetrators
- Explore geographic differences and perform clustering of cities
- Predict victim characteristics using logistic regression
- Compare solved vs. unsolved crimes among racial groups
---

## 📁 Project Structure
.
├── homicide.py # Python analysis and clustering
├── geo_analysis.py # Optional Python geospatial component
├── R_analysis.R # R script for demographic trends and modeling
├── us_cities.csv # Coordinates for U.S. cities
├── population_usafacts.csv # U.S. population data
├── database.csv # Homicide dataset (not committed - see the link below)
└── README.md # This file



---

## 🧪 Analysis Summary

### 🔵 Python: Geospatial Analysis & Clustering

- Cleaned and enriched homicide data with population and geolocation
- Focused on **Texas** and **California** for per-capita analysis
- Applied **KMeans clustering** to group cities by homicide levels
- Generated scatterplots to visualize clusters and outliers

**Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `geopandas`

---

### 🔴 R: Demographic Insights & Predictive Modeling

- Cleaned and filtered demographic data (sex, race, age, relationship, weapon)
- Analyzed trends over time using `ggplot2` and `dplyr`
- Compared crime resolution rates by victim race (Black vs. White)
- Trained a **logistic regression model** to predict **victim sex**
- Evaluated accuracy with **ROC curve** using `pROC`

**Libraries:** `tidyverse`, `pROC`, `gridExtra`, `readr`, `ggplot2`


---

## 📦 Requirements

To run the analysis, install the following dependencies:

### Python:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn geopandas
```
### R:
Install the following packages via CRAN:
```bash
install.packages(c("dplyr", "ggplot2", "pROC", "readr", "gridExtra"))
```

---

## 📚 Dataset
We used the open dataset from Kaggle:
🔗 [Homicide Reports – Murder Accountability Project] (https://www.kaggle.com/datasets/murderaccountability/homicide-reports/data)

Due to file size, it's not stored in the repository. Please download and place it as database.csv in your working directory.

---

## 👥 Authors

Claudia Cortese

Elena Tomasella

Zhao Wei Zhu

Edoardo Bollati

This project was completed for educational purposes at LUISS Guido Carli University, Rome (2023).

--- 

## 📄 License
This project is for educational and non-commercial use only. Please do not redistribute or republish without permission.

