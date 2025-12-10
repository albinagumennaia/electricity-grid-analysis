# ⚡ Electricity Grid Analysis — CIS9650 Project (Group 12)
## 👥 Authors

- Albina Gumennaia  
- Alexander Laurens 
- Chhin Dolma Lama  
- Tanbir Ahmed 

This project analyzes hourly electricity grid data for January 2025 across thirteen U.S. regions.  
Using the Medallion Architecture (Bronze → Silver → Gold), we clean and standardize raw grid data that is loaded **directly from the official EIA website**, create validated regional datasets, and perform descriptive analysis on demand, generation, forecasts, and total interchange.

Our analysis focuses on:
Our analysis focuses on:
- Calculating **daily average demand** by region  
- Calculating **daily average supply** by region  
- Comparing **demand vs. supply**
- Computing summary statistics to describe **hourly variability** across regions  
- Calculating **average daily total interchange** to identify net importers/exporters  
- Comparing **day-ahead forecasted demand vs. actual demand** to evaluate forecast accuracy  
All visualizations and summary tables are produced from the cleaned Gold Layer datasets.

---

## 🗂 Project Structure
```
── CIS9650_Project6_Group12.ipynb        # Main analysis notebook
── README_ELECTRICITY_GRID_ANALYSIS.md   # Project documentation

```

---

## ▶️ How to Run

Install required libraries:

```bash
pip install pandas numpy matplotlib
```

## 🔎 Key Insights

- Day-ahead forecasts tended to underestimate actual demand, especially during colder days.
- High-demand regions often became net importers during peak periods.
- Regions with strong hydropower, nuclear, or gas capacity showed consistent exporting behavior.
- Patterns of hourly variability differed widely across regions due to weather, population, and grid structure.

## ⚠️ Limitations

- Analysis is limited to January 2025 data.
- Forecast accuracy evaluation depends on EIA reporting quality.
- Aggregating to daily averages smooths out some short-term hourly fluctuations.
  
