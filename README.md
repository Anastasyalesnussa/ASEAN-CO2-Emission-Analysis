# 🌏 CO₂ Emission per Capita in ASEAN Countries

## 🧭 Overview  
This project analyzes the trends and disparities in **CO₂ emissions per capita across ASEAN countries**, using open data from [Our World in Data](https://ourworldindata.org/).  
The main goal is to understand how emission patterns have evolved over time and what insights can be drawn in the context of **energy transition and decarbonization** efforts in Southeast Asia.

Interactive Streamlit dashboard can be found [here]([https://ourworldindata.org/](https://asean-co2-emission-dashboard.streamlit.app/))
<img width="1581" height="1001" alt="ASEAN_emission" src="https://github.com/user-attachments/assets/cc2e2a88-a81b-4628-ac82-8c9cc91472f8" />

---

## 🎯 Objectives  
- Explore and clean raw CO₂ emission data.  
- Visualize emission trends by country and year.  
- Compare the latest per capita emissions across ASEAN countries.  
- Analyze temporal correlations between economic growth and emission patterns.  
- Identify countries leading or lagging in emission reduction progress.  

---

## 🧩 Dataset  
**Data Sources:**  
- Global Carbon Budget (2024)  
- Population data (2024) from multiple international sources — processed by *Our World in Data*

**Features:**  
- `country` – ASEAN member country name  
- `year` – Year of observation  
- `annual_co2_emissions_per_capita` – CO₂ emissions per person (tonnes/year)

The dataset was cleaned and standardized into a new file:  
`co2_emission_asean_clean.csv`

---

## 📂 Project Structure
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
│ ├── 01_about_dataset.ipynb # Dataset exploration and cleaning
│ ├── 02_data_cleaning.ipynb # Data preprocessing (optional extension)
│ └── 03_exploratory_analysis.ipynb # Visualization and insights
│
├── README.md # Project overview
├── requirements.txt # Dependencies
└── .gitignore # Git tracking rules
```

---

## 🧠 Key Insights  
- **Singapore** and **Malaysia** have the highest CO₂ emissions per capita due to industrial activity, refining, and export-driven energy sectors.  
- Smaller, high-income economies show higher per capita values because emissions are divided by smaller populations.  
- A high CO₂ per capita does **not always mean poor air quality** — both Singapore and Malaysia maintain strong air pollution control policies and relatively good AQI levels.  
- Most ASEAN countries show **positive correlations between time and CO₂ per capita**, reflecting ongoing industrial and population growth.  

---

## 🛠️ Tools & Libraries  
- **Python**: pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook** for data storytelling  
- **Git** for version control and reproducibility  

---

## 📈 Future Work  
- Extend analysis to **total CO₂ emissions** (not per capita).  
- Correlate emissions with **GDP, energy mix, and renewable adoption rates**.  
- Build **predictive models** to forecast emission trends.  

---

## 👩‍🔬 Author  
**Anastasya Lesnussa**  
Petroleum Engineer | Aspiring Data Scientist in Energy Transition  
📍 *Jakarta, Indonesia*  
