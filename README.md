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
<img width="500" height="300" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/15.png" />

<img width="500" height="300" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />

<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />


<img width="300" height="150" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/1.png" />

---
<h1>📊 Total Vehicles by Model Year </h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/5.png" />

### 📝Explanation

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
<h1>🗺️ Total Vehicles by State : </h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/6.png" />

## 📝 Explanation

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
<h1>🏭 Top 5 Total Vehicles by Make : </h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/7.png" />

## 📝 Explanation

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
<h1> ♻️ Total Vehicles by CAFV Eligibility :</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/8.png" />

## 📝 Explanation

This donut chart represents the **distribution of electric vehicles based on Clean Alternative Fuel Vehicle (CAFV) eligibility**, showing how many vehicles qualify for clean fuel incentives.

### 🔍 Key Insights

- **CAFV Unknown** accounts for the largest share with **69,698 vehicles (46.33%)**.  
  This indicates a significant portion of the dataset lacks confirmed eligibility information, which may be due to missing data or pending classification.

- **CAFV Eligible** vehicles total **62,891 (41.81%)**, representing a substantial segment that qualifies for clean fuel benefits and incentives.

- **CAFV Not Eligible** vehicles make up **17,833 (11.86%)**, forming the smallest share of the dataset.

---

### 📊 Distribution Summary

- Nearly **half of the vehicles have unknown CAFV status**, highlighting a data quality or reporting gap.
- A majority of vehicles with known status are **CAFV eligible**, suggesting strong alignment with clean energy policies.

---

### 🧠 Business Interpretation

- The high percentage of **CAFV-eligible vehicles** reflects positive adoption of clean and compliant EV models.
- The large **unknown category** suggests the need for:
  - Improved data validation
  - Better eligibility tracking
- Policy analysis should focus on vehicles with confirmed eligibility to avoid misinterpretation.

---

  
<h1>🚘 Top 10 Total Vehicles by Model : </h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/9.png" />

## 📝 Explanation

This table displays the **top electric vehicle models ranked by total number of registered vehicles**, along with their manufacturer, EV type, and contribution to the overall dataset.

### 🔍 Key Insights

- **Tesla Model Y** is the most registered EV with **28,502 vehicles (18.95%)**, making it the single most popular model in the dataset.
- **Tesla Model 3** closely follows with **27,709 vehicles (18.42%)**, confirming Tesla’s dominance at the model level.
- Together, **Model Y and Model 3 contribute over 37%** of total EV registrations.

- **Nissan Leaf** ranks third with **13,187 vehicles (8.77%)**, showing strong adoption as an affordable and early-market EV.

- **Tesla Model S and Model X** also appear in the top ranks, reinforcing Tesla’s strong product portfolio.

- **Chevrolet Bolt EV** and **Chevrolet Volt** highlight Chevrolet’s presence across both **BEV and PHEV segments**.

---

### ⚡ EV Type Distribution

- **Battery Electric Vehicles (BEVs)** dominate the top models, indicating stronger consumer preference for fully electric vehicles.
- **Plug-in Hybrid Electric Vehicles (PHEVs)** appear less frequently and contribute smaller shares individually.

---

### 📊 Analytical Interpretation

- EV adoption is **highly concentrated among a few top models**, particularly from Tesla.
- The steep drop in percentages after the top 3 models indicates a **long-tail distribution**, where many models contribute smaller shares.
- Model-level analysis is more impactful than brand-level analysis for understanding **consumer preferences**.

---

<h1>🏙️ Top 5 Cities by Total Vehicles : </h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/10.png" />

## 📝 Explanation

This bar chart highlights the **top 5 cities with the highest number of registered electric vehicles**, showing urban-level concentration of EV adoption.

### 🔍 Key Insights

- **Seattle** leads overwhelmingly with **25,663 vehicles**, accounting for **52.35%** of the total among the top 5 cities.  
  This indicates strong EV adoption driven by urban infrastructure, higher income levels, and sustainability initiatives.

- **Bellevue** ranks second with **7,687 vehicles (15.68%)**, reflecting significant adoption in a major suburban technology hub.

- **Redmond** follows with **5,499 vehicles (11.22%)**, supported by a strong tech workforce and EV-friendly policies.

- **Vancouver** records **5,310 vehicles (10.83%)**, showing steady EV adoption in the region.

- **Bothell** completes the top 5 with **4,861 vehicles (9.92%)**.

---

### 📊 Distribution Summary

- The **top 5 cities together account for 49,020 vehicles**.
- EV registrations are **heavily concentrated in Seattle**, with more than half of the total share.
- Other cities show a relatively balanced distribution compared to the dominant leader.

---

### 🧠 Business Interpretation

- Urban centers and tech-driven cities lead EV adoption.
- Infrastructure availability and environmental awareness play a major role in higher registrations.
- City-level insights can help with:
  - Charging station planning
  - Targeted EV incentive programs
  - Regional demand forecasting

---


<h1>⚡ Electric Vehicle Data Analysis Dashboard-1</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/11.png" />

## 📘 Dashboard Explanation

📊 **Total Vehicles**  
🚗 1,50,422 EVs registered

🔋 **Average Electric Range**  
📏 67.83 miles per vehicle

⚡ **EV Type Split**
- 🔌 **BEV:** 1,16,750 (77.6%)
- 🔁 **PHEV:** 33,672 (22.4%)

🗺️ **Total Vehicles by State**
📍 Washington dominates EV registrations  
🎨 Darker shade = higher EV count  
⚠️ Other states show minimal data presence

📈 **Total Vehicles by Model Year**
- ⏳ Early years (2011–2014): Low adoption
- 📊 Steady growth (2015–2017)
- 🚀 Rapid increase post-2018
- 🏆 Peak in 2023 (~37.1K vehicles)
- ⚠️ 2024 dip due to incomplete data

📉 **Average Reference Line**
📌 Avg vehicles/year ≈ 10.7K  
⬆️ Most recent years are above average

📄 **Export Option**
⬇️ Download dashboard as PDF

💡 **Overall Insight**
🌱 EV adoption is accelerating  
🏙️ Urban & policy-driven regions lead growth  
🔮 Recent years drive future forecasting


---
<h1>⚡ Electric Vehicle Data Analysis Dashboard-2</h1>
<img width="1000" height="600" alt="DASH_BOARD" src= "https://github.com/AvishkarK07/Electric_Vehicle_Analysis/blob/main/image/12.png" />

 ### 📘 Dashboard Overview

♻️ CAFV Eligibility
- ✅ CAFV Eligible → 🚗 62,891 | 📊 41.81%
- ❌ CAFV Not Eligible → 🚗 17,833 | 📉 11.86%
- ❓ CAFV Unknown → 🚗 69,698 | 📊 46.33%

🏙️ Top 5 Cities
- 🏆 Seattle → 🚗 25,663 | 📈 52.35%
- 🥈 Bellevue → 🚗 7,687 | 📊 15.68%
- 🥉 Redmond → 🚗 5,499 | 📊 11.22%
- 🌆 Vancouver → 🚗 5,310 | 📊 10.83%
- 🏘️ Bothell → 🚗 4,861 | 📊 9.92%

🏭 Top 5 Makes
- 🥇 Tesla → 🚗 68,943 | 📈 63.54%
- 🥈 Nissan → 🚗 13,497 | 📊 12.44%
- 🥉 Chevrolet → 🚗 12,025 | 📊 11.08%
- 🚙 Ford → 🚗 7,601 | 📊 7.01%
- 🚘 BMW → 🚗 6,439 | 📊 5.93%

🚘 Top Models
- ⭐ Model Y (Tesla) → 🚗 28,502 | 📊 18.95%
- ⭐ Model 3 (Tesla) → 🚗 27,709 | 📊 18.42%
- 🚗 Leaf (Nissan) → 🚗 13,187 | 📊 8.77%
- 🚙 Model S / X → 📈 Strong adoption
- 🔋 BEV → ⚡ Dominant
- 🔁 PHEV → 📉 Lower share

🎛️ Filters & Controls
- 🗺️ State → Dynamic filtering
- 🔌 EV Type → BEV / PHEV
- 🔢 Top N → Adjustable ranking

💡 Overall Insight
- 🚀 EV adoption accelerating
- 🏙️ Urban & tech cities lead
- 🥇 Tesla dominates market
- ⚠️ CAFV Unknown needs data cleanup



## 📄 License

This dataset is intended for **educational and analytical purposes**.  
Please check the original data source for licensing and usage restrictions.

---

## 🙌 Author

Prepared by **Avishkar Kokate**  
For data analysis, visualization, and portfolio projects

---

⭐ *If you use this dataset, don’t forget to give it a star or credit in your project!*
