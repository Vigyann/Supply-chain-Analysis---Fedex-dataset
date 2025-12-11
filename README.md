# 📦 FedEx Supply Chain Analysis  
A comprehensive data analytics project focused on understanding FedEx shipment patterns using statistical, geographical, and time series techniques.

---

##  Project Overview
This project analyzes a FedEx shipping dataset to uncover insights about delivery performance, carrier efficiency, geographic patterns, and time-based behaviors. The analysis also extends to studying the relationship between FedEx’s **daily shipment volume** and its **stock price**, using financial data fetched through `yfinance`.

The entire workflow is implemented in **Python** using popular data analysis and visualization libraries.

---

##  Technologies & Libraries Used
- **Python**
- **pandas** – data cleaning & manipulation  
- **numpy** – numerical operations  
- **matplotlib**, **seaborn** – visualizations  
- **folium** – interactive geographical maps  
- **yfinance** – FedEx stock data extraction  
- **os** – file handling

---

##  Analyses Performed

### 1. Time & Delivery Analysis
- Shipment distribution by **hour**, **day**, and **month**  
- Identification of peak shipping periods  
- On time vs delayed delivery patterns  
- Average delivery durations  

### 2. Carrier Analysis
- Comparison of carriers on:
  - On time delivery rate  
  - Number of shipments handled  
  - Average delay  
- Ranking of carriers based on performance metrics  

### 3. Geographical Analysis
- Mapping shipment origins and destinations  
- State wise shipment density  
- Identifying regions with high delay frequency  
- Interactive visualizations using **Folium**

### 4. Time Series Analysis
- Daily and monthly trends in shipment volumes  
- Seasonality and cycle detection  
- Trend decomposition  
- Analysis of long term shipping behavior

### 5. FedEx Stock Price & Operations Correlation
- Fetched FedEx stock price using `yfinance`  
- Merged with daily order volume  
- Performed correlation analysis between:
  - Stock price vs daily shipments  
  - Stock price vs delivery delays  
- Insights on whether operational performance affects stock movement  

---

