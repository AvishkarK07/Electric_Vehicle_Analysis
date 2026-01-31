# Electric_Vehicle_Analysis

# 🚗 Electric Vehicle Population Dataset
<img width="1000" height="500" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/dash4.jpg" />

## 📌 Overview

This dataset provides detailed information about **Electric Vehicles (EVs)** registered across different regions in the United States (primarily Washington State). It includes vehicle specifications, geographic details, eligibility classifications, and utility provider information.

The dataset is well-suited for **data analysis, visualization, machine learning projects, and dashboard creation** using tools such as **Python, Tableau, Power BI, and Excel**.

---

## 📊 Dataset Summary

- **Total Records:** 150,482 rows  
- **Total Columns:** 17  
- **Data Type:** Structured tabular data  
- **File Format:** Excel (.xlsx)

---

## 🧾 Column Description

| Column Name | Description |
|------------|------------|
| VIN (1-10) | First 10 characters of the Vehicle Identification Number |
| County | County where the vehicle is registered |
| City | City of registration |
| State | State abbreviation |
| Postal Code | ZIP / Postal code |
| Model Year | Manufacturing year of the vehicle |
| Make | Vehicle manufacturer (e.g., Tesla, BMW, Hyundai) |
| Model | Vehicle model name |
| Electric Vehicle Type | BEV (Battery EV) or PHEV (Plug-in Hybrid EV) |
| Clean Alternative Fuel Vehicle (CAFV) Eligibility | Indicates CAFV eligibility status |
| Electric Range | Maximum electric driving range (in miles) |
| Base MSRP | Base Manufacturer Suggested Retail Price |
| Legislative District | Legislative district number |
| DOL Vehicle ID | Department of Licensing vehicle identifier |
| Vehicle Location | Geospatial point (longitude, latitude) |
| Electric Utility | Electric utility provider(s) |
| 2020 Census Tract | Census tract based on 2020 data |

---

## 🎯 Use Cases

- EV adoption trend analysis  
- Geographic distribution of electric vehicles  
- Comparison between BEV and PHEV vehicles  
- Electric range and model year analysis  
- Utility-wise EV penetration  
- Policy and CAFV eligibility insights  

---

## 📈 Suggested Dashboards & Visuals

- EV registrations by **County / City**  
- BEV vs PHEV distribution (Pie / Donut chart)  
- Electric Range by **Make & Model**  
- Year-wise growth of EV registrations (Line chart)  
- Top manufacturers by number of vehicles (Bar chart)  
- Geo-map using Vehicle Location  

---

## 🛠 Tools Recommended

- **Python:** Pandas, Matplotlib, Seaborn  
- **Tableau / Power BI:** Interactive dashboards  
- **Excel:** Pivot tables and charts  

---

## 🧹 Data Cleaning Notes

- Some fields may contain missing or zero values (e.g., Base MSRP)  
- Electric Utility field may contain multiple providers  
- Vehicle Location is stored as POINT geometry and may need parsing  

---
<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />

<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />

<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />


<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />

---
<h1>Total Vehicles by Model Year</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/5.png" />

### 📊 Total Vehicles by Model Year – Explanation

This chart illustrates the **number of electric vehicles registered by model year**, showing how EV adoption has changed over time.

### 🔍 Key Insights

- **Early Years (2011–2014):**  
  EV adoption was minimal, starting at approximately **0.8K vehicles in 2011** and gradually increasing to around **3–4K**, indicating early market penetration.

- **Gradual Growth Phase (2015–2017):**  
  Registrations increased steadily from **~4.9K to 8.6K**, reflecting growing awareness and improving EV availability.

- **First Major Spike (2018):**  
  A significant rise to **~14.4K vehicles**, crossing the **average benchmark (10.7K)**. This suggests stronger policy support and improved charging infrastructure.

- **Rapid Acceleration (2020–2023):**  
  EV registrations grew sharply:
  - **2021:** ~18.7K  
  - **2022:** ~27.8K  
  - **2023:** **Peak at ~37.1K**  

  This phase represents mass adoption driven by lower battery costs, wider model choices, and increased environmental awareness.

- **Sharp Drop in 2024 (~0.6K):**  
  This decline is due to **incomplete or partial-year data** and should not be interpreted as an actual decrease in EV adoption.

---

### 📈 Average Reference Line

- The dashed line at **~10.7K** represents the **average number of vehicles per model year**.
- Most years before **2018** fall below this average.
- Years from **2018 onward** consistently exceed the average, highlighting accelerated adoption.

---
### 🧠 Business Interpretation

- The visualization shows a **strong upward adoption trend** for electric vehicles.
- Recent years contribute the majority of vehicle registrations.
- **2023** serves as a benchmark year for peak adoption.
- **2024 data should be excluded or handled carefully** in trend and forecasting analyses.

---
<h1>Total Vehicles by State</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/6.png" />

## 🗺️ Total Vehicles by State – Explanation

This choropleth map visualizes the **total number of electric vehicles (EVs) registered across different U.S. states**, providing a geographic perspective on EV adoption.

### 🔍 Key Insights

- **Washington State dominates EV registrations** with approximately **150,082 vehicles**, significantly higher than any other state.  
  This is largely because the dataset is **Washington-state–focused**, not a nationwide sample.

- **Other states show very low counts** (mostly single- or double-digit values), indicating:
  - Limited coverage outside Washington
  - Or partial / sample-level data for non-Washington states

- **Western states** appear slightly more represented than central regions, while many states show minimal or no registrations.

---

### 🎨 Color Interpretation

- **Darker shades** represent higher EV counts.
- **Lighter shades** indicate lower EV registrations.
- The strong contrast highlights the **uneven geographic distribution** of data.

---

### 🧠 Analytical Interpretation

- This map should be interpreted as a **data coverage view**, not a true national EV adoption comparison.
- Washington State is the **primary contributor** to the dataset and should be the main focus for detailed analysis.
- Comparing states directly may lead to **misleading conclusions** due to data imbalance.


---
<h1>Top 10 Total Vehicles by Make</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/7.png" />

## 🏭 Top 5 Total Vehicles by Make – Explanation

This horizontal bar chart displays the **top 5 electric vehicle manufacturers by total number of registered vehicles**, highlighting market dominance among leading brands.

### 🔍 Key Insights

- **Tesla** leads overwhelmingly with **68,943 vehicles**, accounting for **63.54%** of the total vehicles among the top 5 makes.  
  This indicates Tesla’s strong brand presence, wider model adoption, and early leadership in the EV market.

- **Nissan** ranks second with **13,497 vehicles (12.44%)**, showing steady adoption driven by popular models such as the Leaf.

- **Chevrolet** follows closely with **12,025 vehicles (11.08%)**, reflecting its contribution through affordable EV offerings.

- **Ford** holds the fourth position with **7,601 vehicles (7.01%)**, indicating growing but still moderate EV adoption.

- **BMW** completes the top 5 with **6,439 vehicles (5.93%)**, representing a smaller yet premium segment of the EV market.

---

### 📊 Distribution Summary

- The **top 5 manufacturers together account for 100%** of vehicles shown in this view.
- There is a **highly skewed distribution**, with Tesla alone contributing nearly two-thirds of the total.
- The sharp drop from Tesla to the second-ranked manufacturer highlights **market concentration**.

---

### 🧠 Business Interpretation

- The EV market in this dataset is **dominated by a single manufacturer (Tesla)**.
- Other manufacturers contribute meaningfully but remain far behind the market leader.
- This insight can support:
  - Competitive market analysis
  - Manufacturer performance benchmarking
  - Strategic planning and forecasting

---

### 🎛️ Interactivity Notes

- The **Top N parameter** allows dynamic adjustment of the number of manufacturers displayed.
- **EV Type and State filters** enable focused analysis by vehicle category or geographic region.

---
<h1>Total Vehicles by CAFV Eligibility</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/8.png" />

---
<h1>Top 10 Total Vehicles by Model</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/9.png" />

---
<h1>TOP 5 cites</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/10.png" />

---
<h1>Dashboard</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/11.png" />


---
<h1>Dashboard</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/12.png" />



## 📄 License

This dataset is intended for **educational and analytical purposes**.  
Please check the original data source for licensing and usage restrictions.

---

## 🙌 Author

Prepared by **Avishkar Kokate**  
For data analysis, visualization, and portfolio projects

---

⭐ *If you use this dataset, don’t forget to give it a star or credit in your project!*
