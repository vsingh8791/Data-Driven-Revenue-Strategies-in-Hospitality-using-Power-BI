
# 📊 Revenue Insights in Hospitality Domain  

## 📌 Overview  

This project analyzes revenue trends in the hospitality industry using **Power BI**. The goal is to gain insights into key performance indicators (KPIs) such as occupancy rates, average daily rates (ADR), and revenue per available room (RevPAR).  

## 🗂 Dataset  

The project utilizes multiple datasets related to hotels, rooms, bookings, and dates:  

| File Name                         | Description |
|-----------------------------------|-------------|
| `dim_date.csv`                   | Contains time-based data for analysis (days, weeks, months, etc.). |
| `dim_hotels.csv`                 | Details of hotels, including name, category, and city. |
| `dim_rooms.csv`                  | Room details such as type, class, and capacity. |
| `fact_aggregated_bookings.csv`    | Aggregated booking data for trend analysis. |
| `fact_bookings.csv`               | Transactional booking records with revenue details. |

For more details on column descriptions, refer to the **Metadata** section below.

## 📊 Power BI Dashboard  

- **File Name:** `Revenue Insights in Hospitality Domain.pbix`  
- **Description:** The Power BI dashboard visualizes revenue performance across different dimensions such as time, customer segments, and geographic locations.  

## 📑 Metadata  

The **meta_data_hospitality.txt** file provides detailed descriptions of the dataset columns. Key attributes include:  

- **dim_date.csv:** Contains date information, including weekday/weekend classification.  
- **dim_hotels.csv:** Defines properties by ID, name, category (Luxury/Business), and city.  
- **dim_rooms.csv:** Lists room types and classifications (Standard, Elite, Premium, Presidential).  
- **fact_aggregated_bookings.csv:** Aggregated data on check-ins, room categories, and successful bookings.  
- **fact_bookings.csv:** Detailed transaction-level booking data, including revenue generated and realized.  

## 📏 Metrics  

The **metrics list.xlsx** file includes calculated KPIs such as:  

- **Average Daily Rate (ADR)**  
- **Revenue Per Available Room (RevPAR)**  
- **Occupancy Rate**  
- **Cancellation Rate**  
- **Customer Segmentation Metrics**  

## 🔑 Key Insights  

- 📈 Trends in revenue generation over different seasons.  
- 🏨 Occupancy rates and their impact on revenue.  
- 🎯 Identifying high-value customer segments.  
- 💡 Recommendations for improving profitability.  

## 📌 How to Use  

1. Clone this repository.  
2. Download the dataset files and the Power BI `.pbix` file.  
3. Open the `.pbix` file in **Power BI Desktop**.  
4. Load the datasets and refresh queries.  
5. Explore the interactive dashboards and insights.  

## 💡 Future Improvements  

- Integrate real-time data updates.  
- Add predictive analytics for revenue forecasting.  
- Expand analysis to multiple hotel chains.  

---
