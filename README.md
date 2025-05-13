```markdown
# 📊 COVID-19 Global Data Tracker

This project analyzes global COVID-19 trends using publicly available time-series datasets from [Johns Hopkins University CSSE](https://github.com/CSSEGISandData/COVID-19). It focuses on confirmed cases and deaths across countries such as **Kenya**, **United States**, and **India**, incorporating data cleaning, exploratory analysis, and visualizations.

> **Author**: Shamim Gitungo  
> **Notebook Format**: Jupyter Notebook (`.ipynb`)  
> **Primary Dataset**: JHU CSSE COVID-19 Time Series Data

---

## 📌 Objectives

- Import and clean COVID-19 data from JHU CSSE
- Analyze time trends in confirmed cases and deaths
- Compare pandemic impacts across key countries
- Create visualizations including line plots and a choropleth map
- Summarize key insights from the data

---

## 📂 Dataset Source

Data is pulled directly from the following raw CSV files:

- [Confirmed Cases CSV](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)
- [Deaths CSV](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)

---

## 🛠️ Requirements

Install the required Python libraries:

```bash
pip install pandas matplotlib seaborn plotly
```

**Python version:** Python 3.8+ recommended

---

## 📈 Features

- Cleans and merges confirmed and death time-series datasets
- Converts time-series columns into tidy long-format data
- Calculates death rates (deaths / cases)
- Visualizes trends in total cases and deaths over time
- Creates a global choropleth map using Plotly
- Provides narrative insights and interpretations

---

## 🌍 Countries Covered

- **Kenya**
- **United States**
- **India**

These are used for comparative analysis. The choropleth map includes broader country data.

---

## 📊 Visualizations

- **Line charts** for total cases and deaths over time per country
- **Choropleth map** of global total cases (latest date)
- Summary statistics tables

---

## 🔍 Key Insights

- U.S. leads in total cases and deaths
- Kenya shows the lowest overall counts but relatively higher death rates
- India experienced a major spike in early 2021
- Disparities reflect population size, healthcare, and testing/reporting capacity

---

## 🚀 Future Enhancements

- Add vaccination data from sources like *Our World in Data*
- Build an interactive dashboard with **Streamlit**
- Analyze impacts of interventions (e.g. lockdowns, mandates)

---

## 📜 License

This project is for educational and research purposes. Data used is sourced from publicly available repositories.
```
