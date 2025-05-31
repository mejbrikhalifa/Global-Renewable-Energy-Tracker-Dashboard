# **Global-Renewable-Energy-Tracker-Dashboard**
An interactive Tableau dashboard and Python-powered data pipeline analyzing the global state of renewable energy from 1990 to 2024. This project visualizes capacity trends and geographic distributions using official data from the **International Energy Agency (IEA)** and the **Global Energy Monitor** (June 2024).

## **Dashboard Overview**

The dashboard highlights key global insights into renewable energy trends, featuring:

- **Total global renewable energy capacity**
- **Solar**, **Wind**, and **Hydropower** shares of total capacity
- **Top N producing countries** with capacity and percent share
- **Yearly capacity growth curve** (1990–2024)
- **Regional and country-level distribution**
- **Repartition by energy type**
- **Sortable table of total capacity by country**
- **Interactive filters**: by Region, Energy Type, and Top N Countries

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

- **Solar and Wind** dominate the global renewable portfolio in recent years.
- **China**, **United States**, and **Brazil** lead in installed renewable capacity.
- The global capacity has grown exponentially since 1990, with strong regional differences.
- The **Asia** region has seen the largest increase, while **Africa** still shows untapped potential.
- Capacity-based weighting reveals deeper insights than simple project counts.

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


