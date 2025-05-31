# **Global-Renewable-Energy-Tracker-Dashboard**
An interactive Tableau dashboard and Python-powered data pipeline analyzing the global state of renewable energy from 1990 to 2024. This project visualizes capacity trends and geographic distributions using official data from the **International Energy Agency (IEA)** and the **Global Energy Monitor** (June 2024).

## **Dashboard Overview**

The dashboard highlights key global insights into renewable energy trends, featuring:

- **Total global renewable energy capacity**
- **Solar, Wind, and Hydropower shares of total capacity**
- **Top N producing countries with capacity and percent share**
- **Yearly capacity growth curve (1990–2024)**
- **Regional and country-level distribution**
- **Repartition by energy type**
- **Sortable table of total capacity by country**
- **Interactive filters: by Region, Energy Type, and Top N Countries**

### **The Full Tableau Dashboard is attached as .twb and .twbx: Renewable Energy Dashboard_Dr Khalifa Mejbri**

## **Tools & Technologies**

- **Python**: `pandas`, `matplotlib` for data cleaning, transformation, and exploratory analysis
- **Tableau**: for creating the interactive dashboard
- **Jupyter Notebooks**: for reproducible preprocessing
- **GitHub**: for version control and documentation

---

## **Data Processing**

We used Python to clean and transform raw renewable energy project-level data. Key steps included:

- Combining the datasets of the different renewable energies in one dataset
- Standardizing fields (`Region`, `Country`, `Energy Type`, `Status`)
- Aggregating `Capacity_MW` by country, region, and year
- Identifying top producing countries per region
- Calculating the global share of energy types, weighted by capacity (MW)
- Exporting ready-to-use datasets for Tableau visualization

📁 See the attched file (**Renewable_Energies_Data_Preprocessing.ipynb**) for full details.

## **Key Insights**
- **Wind Energy** leads globally in installed capacity, representing **41%**, followed by **Solar Energy (30%)** and **Hydropower (27%)**, while **Bioenergy** and **Geothermal** Energy contribute marginally.
- **Asia dominates** the global renewable energy capacity with nearly **49%**, followed by the **Americas (19.7%)** and Europe **(19.6%)**. **Africa** and **Oceania** share the smallest portions.
- Among the **Top 10 producing countries**, **China** alone accounts for nearly half **(48.9%)** of the global installed capacity, followed by the **USA (12.6%)**, **Brazil (8.7%)**, and **Australia (6.5%)**. Other significant contributors include **India, Spain, UK, Sweden, Vietnam, and Canada**.
- **Renewable capacity growth has accelerated significantly since 2006**. From modest beginnings (~7,000 MW in 1990), global installations soared to over **342,000 MW by 2023**, highlighting a strong upward trend.

## License & Attribution

This project uses data provided by:
- **International Energy Agency (IEA)**
- **Global Energy Monitor, Global Wind Power Tracker (June 2024 release)**

Distributed under the [**Creative Commons Attribution 4.0 International License**](https://creativecommons.org/licenses/by/4.0/).

## **Acknowledgements**

Special thanks to the creators of the original datasets and the open-source tools that made this analysis possible.

## **Future Work**

- Time-series forecasting of renewable capacity growth
- Integration of CO₂ emissions reductions from renewable expansion
- Deeper dive into policy impact by country or region


