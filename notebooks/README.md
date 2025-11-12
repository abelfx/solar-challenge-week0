# 📓 Notebooks Overview

This folder contains all the **Exploratory Data Analysis (EDA)** and visualization notebooks developed for the **Solar Data Discovery — Week 1 Challenge**.

Each notebook focuses on a different stage of data understanding and analysis for the three countries:
**Benin**, **Togo**, and **Sierra Leone**.

---

## 📚 Notebooks Description

| Notebook | Description | Status |
|-----------|--------------|--------|
| **benin_eda.ipynb** | Performs data profiling, cleaning, and exploratory analysis for Benin’s solar dataset. Includes summary statistics, missing value handling, and irradiance trend visualization. | ✅ Completed |
| **togo_eda.ipynb** | Similar EDA process for Togo’s dataset. Analyzes temperature, humidity, and irradiance variations. | ✅ Completed |
| **sierraleone_eda.ipynb** | EDA for Sierra Leone’s dataset. Focuses on humidity effects, irradiance variability, and data quality. | ✅ Completed |
| **compare_countries.ipynb** | Combines the three cleaned datasets to compare GHI, DNI, and DHI values across countries. Includes summary tables, boxplots, and ANOVA testing. | 🚧 In Progress |

---

## 🧭 Recommended Execution Order

1. `benin_eda.ipynb`  
2. `togo_eda.ipynb`  
3. `sierraleone_eda.ipynb`  
4. `compare_countries.ipynb` (after all clean CSVs are generated)

---

## 🧰 Outputs Generated

- Cleaned datasets saved in `../data/`
  - `benin_clean.csv`
  - `togo_clean.csv`
  - `sierraleone_clean.csv`
- Visualizations for:
  - GHI, DNI, DHI trends over time
  - Cleaning impact on module performance
  - Correlation and heatmap analyses
  - Temperature vs. Humidity relationships
  - Wind distribution and bubble charts

---

## 🧠 Insights Highlight

- **Benin**: Strong daily solar consistency and low data variability.  
- **Togo**: Moderate GHI with balanced humidity influence.  
- **Sierra Leone**: High humidity and intermittent irradiance due to cloud cover.  

---

## 📝 Notes

- Each notebook uses consistent cleaning and EDA pipelines for comparability.  
- Raw and cleaned datasets are excluded from Git tracking (`data/` is in `.gitignore`).  
- Visualizations were created using **Matplotlib**, **Seaborn**, and **Plotly** for interactivity.  

---

**Author:** Abel Tesfa  
📊 *10 Academy AI Mastery Challenge — Week 0*  
