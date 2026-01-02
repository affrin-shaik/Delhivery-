# Delhivery Logistics & Supply Chain Analysis | Power BI

## 📊 Project Overview
This project provides a data-driven analysis of **Delhivery’s** logistics operations. The dashboard focuses on end-to-end delivery performance, route efficiency, and service level agreement (SLA) compliance. It is designed to help operations managers identify delays, optimize delivery routes, and improve overall supply chain transparency.

## 🚀 Key Performance Indicators (KPIs)
The dashboard monitors critical logistics metrics:
* **Total Shipments:** Total volume of orders processed.
* **On-Time Delivery (OTD) %:** Percentage of shipments delivered within the promised timeframe.
* **Average Delivery Time:** The mean time taken from pickup to final destination.
* **Distance vs. Time:** Correlation between travel distance and actual transit time to identify route inefficiencies.
* **SLA Breach Count:** Total number of shipments that exceeded the expected delivery date.

## 🛠️ Technical Implementation
### Data Transformation (Power Query)
* **Geospatial Analysis:** Cleaned and standardized source and destination city/state data for accurate mapping.
* **Time Calculation:** Created custom columns to calculate the difference between *Actual* vs. *Estimated* time of arrival (ETA).
* **Status Classification:** Categorized shipments into 'Delivered', 'In-Transit', and 'Returned' for real-time status tracking.

### Data Modeling & DAX
* **DAX Measures:** Developed advanced measures for **Weighted Average Delivery Time** and **Route-wise Efficiency Scores**.
* **Dynamic Ranking:** Implemented logic to highlight top-performing delivery hubs and underperforming logistics corridors.

## 📈 Dashboard Highlights
* **Route Efficiency Map:** A geospatial visualization showing peak delivery volume routes and high-delay zones.
* **Monthly Performance Trends:** Analysis of volume surges during festive seasons or promotional events.
* **State-wise Breakdown:** A comparative analysis of logistics performance across different Indian states.
* **Logistics Funnel:** Tracking the transition from "Warehouse Pick-up" to "Last-mile Delivery."

## 💡 Business Insights
* **Bottleneck Identification:** Discovered that specific transit hubs were causing 30% of total SLA breaches due to processing delays.
* **Last-Mile Optimization:** Analysis revealed that "Last-mile" delivery accounts for the highest variance in total delivery time, suggesting a need for localized partner optimization.
* **Route Planning:** Identified that certain longer routes actually have faster delivery times due to better highway infrastructure, recommending a shift away from shorter but congested urban paths.

## 📂 Repository Structure
```text
├── Data/                   # Logistics datasets (anonymized)
├── Dashboard/              # Delhivery_Analysis.pbix file
├── Screenshots/            # Dashboard view & UI clips
└── README.md               # Project documentation# Delhivery-
