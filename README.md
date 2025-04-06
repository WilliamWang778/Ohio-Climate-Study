# 🌧️ Ohio Climate & Flood Analysis (Raccoon Creek, 2020)

**Data Systems | Python, Pandas, Matplotlib**  
📍 *Granville, OH | October 2024*

## 🧠 Overview

This project investigates the **2020 flooding event in Raccoon Creek, Ohio**, by analyzing multiple hydrological and meteorological datasets. The goal is to understand the **causes**, **patterns**, and **climate implications** of the flood using time-aligned and cleaned data from the **National Weather Service (NWS)**.

The analysis is presented in a research-style Jupyter Notebook, combining **statistical reasoning** and **visualizations** to support a data-driven narrative about climate and flooding.

---

## 💾 Datasets

All datasets were sourced from the **National Weather Service (NWS)** and contain measurements from various sensors and stations in Ohio during 2020.

- `discharge_2020.csv`  
  - **15-minute interval data**  
  - Measures water discharge (flow rate, in cubic feet per second) from Raccoon Creek  
  - Contains timestamps and discharge values for the entire 2020 calendar year

- `gage_height_2020.csv`  
  - **15-minute interval data**  
  - Records gage height (in feet), indicating the water level of the creek  
  - Used to confirm flood peak and water rise trends

- `weather_2020.csv`  
  - **Daily aggregated data**  
  - Includes total **precipitation (inches)** and **temperature highs/lows**  
  - Provides context on weather patterns preceding and during the flood

---

## 🗂️ Project Structure

- `data/`  
  Raw datasets from the National Weather Service (2020)

- `notebooks/`  
  Jupyter Notebook with full analysis
  - `ohio_flood_analysis.ipynb` — Cleaned, visualized, and interpreted flood/climate data

- `output/`  
  Generated visualizations from the analysis
  - `flood_peak_plot.png` — Time series graph showing flood peak vs rainfall

- `README.md`  
  Project overview and documentation



---

## 🔧 Tools & Techniques

- 📊 **Pandas** for time series parsing, cleaning, merging, and aggregation  
- 📈 **Matplotlib** for visualizing climate and flooding patterns  
- ⏱️ **Time alignment** across different temporal resolutions  
- 🧹 Handling missing values and resolving format inconsistencies  
- 📓 Structured analysis in **Jupyter Notebook**

---

## 📊 Key Results

- 🕒 Identified flood peak on **March 20, 2020** using discharge & gage height curves  
- 🌧️ Detected a strong **correlation between rainfall spikes and flood rise**  
- 🔁 Unified 15-min and daily data using aggregation (mean/max) for comparison  
- 📉 Created a **multi-axis time series plot** showing climate-flood interaction
