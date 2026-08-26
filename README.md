<div align="center">

# 🦠 COVID-19 Analysis & Visualization using Plotly Express

### Interactive data storytelling on the global pandemic — bar charts, bubble charts, choropleth maps & word clouds

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Express-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![WordCloud](https://img.shields.io/badge/WordCloud-Text%20Viz-2E8B57?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>

---

## 📌 Overview

This project explores the **global spread of COVID-19** through interactive, high-quality visualizations built with **Plotly Express**. It goes beyond static charts — every plot in this notebook is interactive, hoverable, and animation-ready, turning raw pandemic data into an explorable story.

The analysis covers country-level comparisons, continent-wise trends, time-series progression, animated world maps, and even text-based insight into reported death conditions via word clouds.

---

## ✨ Key Features

| Category | What's Inside |
|---|---|
| 📊 **Bar Charts** | Country-wise comparison of Total Cases, Deaths, Recovered & Tests (vertical & horizontal) |
| 🫧 **Bubble Charts** | Continent-wise & country-wise scatter plots with size/color encoding (log-scaled) |
| 📈 **Time-Series** | Confirmed cases, deaths & recoveries over time — global and USA-specific |
| 🗺️ **Choropleth Maps** | Animated world maps tracking Confirmed & Recovered cases day-by-day |
| ☁️ **Word Clouds** | Text visualization of reported death conditions from CDC data |
| 🧹 **Data Cleaning** | Handling missing values, dropping redundant columns, filtering country-specific subsets |

---

## 🗂️ Datasets Used

| File | Description |
|---|---|
| `covid.csv` | Country-level snapshot — total cases, deaths, recovered, tests, population |
| `covid_grouped.csv` | Daily time-series data by country (Confirmed / Deaths / Recovered / Active) |
| `coviddeath.csv` | CDC data on death conditions & comorbidities |

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data cleaning & manipulation
- **Plotly Express / Plotly Graph Objects** — interactive visualizations
- **Matplotlib** — rendering word clouds
- **WordCloud** — text-frequency visualization
- **Jupyter Notebook**

---

## 🚀 Project Workflow

```
1. Import Libraries        →  plotly, pandas, matplotlib, wordcloud
2. Load Datasets           →  covid.csv, covid_grouped.csv, coviddeath.csv
3. Clean & Prepare Data    →  drop NaNs, filter columns, subset by country
4. Bar Chart Analysis      →  top-15 countries by cases/deaths/tests
5. Bubble Chart Analysis   →  continent-wise & country-wise (log scale)
6. Time-Series Analysis    →  global trend + USA deep-dive
7. Geo Visualization       →  animated choropleth maps by date
8. Text Visualization      →  word clouds on death conditions
```

---

## 📁 Repository Structure

```
Covid19-Analysis-and-Visualization-Using-Plotly-Express/
│
├── covid-19-analysis-and-visualization-using-plotly.ipynb   # Main notebook
├── covid.csv                                                 # Country-level dataset
├── covid_grouped.csv                                         # Time-series dataset
├── coviddeath.csv                                             # Death conditions dataset
└── README.md                                                  # You are here
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/Covid19-Analysis-and-Visualization-Using-Plotly-Express.git
cd Covid19-Analysis-and-Visualization-Using-Plotly-Express

# 2. Install dependencies
pip install pandas plotly matplotlib wordcloud jupyter

# 3. Launch the notebook
jupyter notebook covid-19-analysis-and-visualization-using-plotly.ipynb
```

---

## 📷 Sample Visuals

> Add screenshots or GIFs of your key charts here (bar chart, bubble chart, choropleth map) — visuals massively boost engagement on GitHub & LinkedIn.

```
docs/
├── bar-chart.png
├── bubble-chart.png
└── choropleth-map.gif
```

---

## 🎯 What This Project Demonstrates

- Cleaning and structuring real-world, messy pandemic data
- Choosing the right chart type for the right story (comparison vs. trend vs. geography vs. text)
- Building animated, interactive visualizations instead of static plots
- Communicating multi-dimensional data (size + color + hover context) clearly

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

---

<div align="center">

**⭐ If you found this project useful, consider giving it a star!**

</div>
