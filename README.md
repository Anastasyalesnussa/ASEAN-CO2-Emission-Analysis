# CO₂ Emission per Capita in ASEAN.

## Overview  
This project analyzes the trends and disparities in **CO₂ emissions per capita across ASEAN countries**, using open data from [Our World in Data](https://ourworldindata.org/).  

Interactive Streamlit dashboard can be found [here](https://asean-co2-emission-dashboard.streamlit.app/).
<img width="1581" height="1001" alt="ASEAN_emission" src="https://github.com/user-attachments/assets/cc2e2a88-a81b-4628-ac82-8c9cc91472f8" />

---

## Objectives  
- Assesing CO2 Emission per Capita in ASEAN.
- Visualize and compare the latest per capita emissions across ASEAN.  
- Analyze temporal correlations between economic growth and emission patterns.  
- Identify countries leading or lagging in emission reduction progress.
- Gain insight that can support discussions around sustainable development and decarbonization policies in Southeast Asia.

---

## Key Insights  
- In 2023 **Brunei** have the highest CO₂ emissions per capita, exceeding 25 tonnes per person. This reflects its oil-export-oriented economy, small population and energy-intensive industries. While correlation between year and CO2 per capita shows slightlty negative correlation that suggests a possible stabilization or reduction in emission.
- **Singapore** and **Malaysia** emited around 8-9 tonnes per person tend to have more energy-intensive industries, contributing to elevated emissions despite smaller populations.
- **Thailand**, **Vietnam**, and **Laos** occupy the mid range, each between 3-4 tonnes per person, consistent with industrial expansion and increased electricity consumption.
- **Indonesia**, despite being one of the region's largest emitters in total terms, shows relatively low per capita emissions 2-3 tonnes due to its large population base.
- **Philippines**, **Cambodia**, and **Myanmar** remain the lowest emitters, below 2 tonnes per person, reflecting slower industrialization. 
- A high CO₂ per capita does **not always mean poor air quality** — Brunei, Singapore and Malaysia maintain strong air pollution control policies and relatively good AQI levels.  

---

## Dataset  
**Data Sources:**  
- Global Carbon Budget (2024)Population based on various sources (2024) – with major processing by **Our World in Data**

**Features:**  
- `country` – ASEAN member country name  
- `year` – Year of observation  
- `annual_co2_emissions_per_capita` – CO₂ emissions per person (tonnes/year)

The dataset was cleaned and standardized into a new file:  
`co2_emission_asean_clean.csv`

---

## Project Structure
```plaintext
CO2-Emission-ASEAN/
│
├── data/
│ ├── raw/
│ │ └── co2_emission_raw.csv
│ └── processed/
│ └── co2_emission_asean_clean.csv
│
├── notebooks/
│ ├── 01_about_dataset.ipynb 
│ ├── 02_data_cleaning.ipynb 
│ └── 03_exploratory_analysis.ipynb 
│
├── README.md 
├── requirements.txt 
└── .gitignore 
```

---

## Tools & Libraries  
- **Python**: pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook** for data storytelling  
- **Git** for version control and reproducibility  

---

## Future Work  
- Extend analysis to **total CO₂ emissions** (not per capita).  
- Correlate emissions with **GDP, energy mix, and renewable adoption rates**.  
 
