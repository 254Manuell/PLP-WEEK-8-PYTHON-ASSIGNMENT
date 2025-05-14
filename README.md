# 🌍 Global COVID-19 Data Analysis (Jupyter Notebook)

A comprehensive data exploration and visualization notebook analyzing the global impact of COVID-19 with a focus on key countries: **Kenya, United States, and India**. The project leverages real-world data to uncover patterns, highlight disparities in vaccination rollouts, and visualize global pandemic trends using cutting-edge tools like **Plotly**, **Seaborn**, and **Pandas**.

---

## 📁 Project Overview

This project walks through the full data pipeline:

1. **Data Loading & Exploration**  
2. **Data Cleaning**  
3. **Exploratory Data Analysis (EDA)**  
4. **Vaccination Progress Visualization**  
5. **Choropleth Mapping (Optional)**  
6. **Narrative Insights**

---

## 📊 Dataset

- **Source**: [Our World in Data (OWID)](https://ourworldindata.org/covid-data)
- **File**: `owid-covid-data.csv`
- **Scope**: Global COVID-19 statistics including case counts, deaths, vaccination numbers, and health system metrics.

---

## 🧪 Technologies Used

| Tool / Library    | Purpose                            |
|-------------------|-------------------------------------|
| `pandas`          | Data manipulation & wrangling       |
| `matplotlib`      | Basic data visualization            |
| `seaborn`         | Statistical plotting                |
| `plotly.express`  | Interactive choropleth maps         |
| `numpy`           | Numerical operations                |
| `jupyter`         | Interactive Python analysis         |

---

## 📌 Key Features

### ✅ 1. Data Cleaning
- Filters selected countries.
- Converts date to datetime format.
- Handles missing values via interpolation.

### ✅ 2. Exploratory Visualizations
- **Line charts** for case & death progression.
- **Bar charts** comparing vaccination rates.
- **Death rate trends** across time.
- Optional **heatmap** of feature correlations.

### ✅ 3. Vaccination Rollout Analysis
- Cumulative vaccination charts.
- % of population vaccinated.
- Pie charts for vaccinated vs. unvaccinated (optional).

### ✅ 4. Global Choropleth Maps
- Total cases (red to black scale).
- % vaccinated per country.

---

## 📈 Key Insights

- 🇺🇸 **United States** led in cumulative vaccinations.
- 🇮🇳 **India** showed multiple infection waves with high volatility.
- 🇰🇪 **Kenya** lagged significantly in vaccine rollout.
- 📉 Death rate trends varied, with some countries showing unusually high ratios.
- 🌍 Several nations plateaued in reported cases post-2023, possibly due to underreporting.

---

## 🚀 Getting Started

### 🧰 Requirements

Ensure you have the following installed:

```bash
pip install pandas matplotlib seaborn plotly
```

### 📂 How to Use

1. Open the Jupyter notebook:
   ```
   jupyter notebook Week_8_Python_Assignment.ipynb
   ```
2. Step through each cell sequentially to:
   - Load and clean data
   - Perform visual analysis
   - Interpret findings

---

## 📎 File Structure

```text
📦Project
 ┣ 📜 owid-covid-data.csv
 ┣ 📔 Week_8_Python_Assignment.ipynb
 ┗ 📄 README.md
```

---

## 🙋🏽‍♂️ Author & Attribution

This notebook was created by [254Manuell](https://github.com/254Manuell) as part of the **Power Learn Project – Week 8 Assignment**.

Dataset by [Our World in Data](https://ourworldindata.org/).  
Feel free to contribute or suggest improvements via pull requests or issues!

---
