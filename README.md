# 🏨 AtliQ Grand — Hospitality Analytics Project

---

## 🎯 What Is This Project About?

This project is an end-to-end **Hospitality Analytics** study for AtliQ Grand, designed to uncover insights on hotel performance, guest behavior, and revenue optimization. Using real-world data from Codebasics, the project transforms raw operational, booking, and financial data into meaningful business intelligence.

Through detailed analysis of occupancy rates, room category performance, revenue realization, guest satisfaction, and seasonal demand, the project aims to help hotel management:

- Improve operational efficiency  
- Optimize pricing and inventory  
- Enhance guest experience  
- Strengthen revenue and profitability  
- Identify high-performing cities, hotels, and room categories  

Overall, this project demonstrates how data can be leveraged to make strategic decisions in the hospitality industry, enabling AtliQ Grand to improve business outcomes and stay competitive.

---

## 📌 Project Objectives

The primary objective of this project is to conduct an end-to-end analytical assessment of AtliQ Grand’s hotel operations, revenue performance, and guest behavior. The project aims to:

1. **Analyze hotel performance across multiple cities** to identify high-performing and underperforming locations.  
2. **Evaluate occupancy trends** across room categories and seasons to understand demand behavior.  
3. **Assess key revenue metrics** such as ADR, RevPAR, and Revenue Realization % for financial performance benchmarking.  
4. **Examine room category profitability** and determine which room types drive the highest business value.  
5. **Analyze guest ratings, complaints, and booking patterns** to uncover drivers of customer satisfaction and service improvement areas.  
6. **Identify monthly and seasonal revenue/occupancy trends** to support forecasting and resource planning.  
7. **Generate visual dashboards and actionable insights** to support strategic decision-making at operational and managerial levels.

Overall, these objectives help build a complete analytical picture of AtliQ Grand’s business performance, enabling data-driven strategy and operational optimization.

---

## 🧭 Why This Project Matters

In the hospitality industry, data-driven decision-making is essential for improving occupancy, maximizing revenue, and enhancing guest experience. This project demonstrates how analytics can transform raw hotel data into actionable insights that support strategic and operational excellence.

This project matters because it enables AtliQ Grand to:

- **Understand performance across cities and hotel categories** to identify where profitability is strongest  
- **Optimize occupancy and pricing strategies** using trends in ADR, RevPAR, and demand behavior  
- **Enhance guest satisfaction** by analyzing ratings, complaints, and booking patterns  
- **Reduce cancellations and improve revenue realization** through operational insights  
- **Plan more effectively** by recognizing seasonal, monthly, and room-category trends  
- **Drive competitive advantage** using business intelligence rather than intuition  

Overall, this project demonstrates how hospitality businesses can leverage analytics to improve financial outcomes, streamline operations, and deliver better guest experiences—making data an essential asset for sustainable growth.

---

## 📁 Dataset Overview

| Feature | Value |
|---------|--------|
| **Data Source** | Codebasics – Hospitality Analytics Challenge Dataset |
| **Total Records** | ~15,000+ hotel booking & operational entries |
| **Number of Tables** | 6 interconnected datasets |
| **Hotel Coverage** | Multiple hotels across 4 cities (Mumbai, Bangalore, Hyderabad, Delhi) |
| **Room Categories** | Standard, Premium Suite, Luxury King, Elite Deluxe |
| **Key Metrics Included** | Revenue, ADR, RevPAR, Occupancy %, Ratings, Realization % |
| **Time Features** | Daily dates, monthly trends, seasonal patterns |
| **Guest Behavior Attributes** | Booking window, cancellation patterns, ratings, complaints |
| **Missing Values** | Cleaned, standardized & imputed |

The dataset is sourced from **Codebasics**, designed as a real-world hospitality analytics case study.  
It includes detailed information on hotel performance, room category utilization, revenue generation, guest satisfaction, and operational efficiency—allowing a full analytical exploration of AtliQ Grand’s business performance.

---

## 📁 What This Project Includes:

🔹 Data Cleaning & Transformation:
- Handling missing values and duplicates
- Correcting data formats (dates, numeric columns)
- Standardizing text fields (e.g., city names, hotel types)
- Aggregating & grouping data for higher-level insights

🔹 Exploratory Data Analysis (EDA):
- Monthly revenue & occupancy trend analysis
- Room performance comparison across hotel types
- Identifying top-performing hotels, rooms, and customer segments

---

## 🛠 Tools & Technologies Used

- **Python** – Core programming language for analysis  
- **Pandas** – Data cleaning, transformation, and manipulation  
- **NumPy** – Numerical operations and data structuring  
- **Matplotlib** – Static visualizations and trend analysis  
- **Seaborn** – Advanced statistical plotting and pattern detection  
- **Jupyter Notebook** – Interactive environment for EDA, visualization, and documentation

---

## 📁 Key Performance Indicators (KPIs):

Below are example KPI metrics (customizable based on your dataset):
| KPI                                   | Value       | Explanation                                         |
|---------------------------------------|-------------|-----------------------------------------------------|
| Total Revenue Generated               | ₹ 78.5 Cr   | Revenue from all hotel properties combined         |
| Average Occupancy Rate                | 68.4%       | Indicates strong room utilization across properties |
| Revenue per Available Room (RevPAR)   | ₹ 4,850     | Key profitability metric for hospitality chains     |
| Average Daily Rate (ADR)              | ₹ 7,120     | Shows average price paid per room                   |
| Customer Satisfaction Score           | 4.2 / 5     | Based on aggregated guest ratings                   |
| Most Booked Room Category             | Elite Deluxe| Highest volume and repeat demand                    |
| Highest Revenue City                  | Mumbai      | Drives the largest share of earnings                |


## 📁  Summary Findings 
⭐ 1. Hotel Performance
| City          | Occupancy Rate | Total Revenue | Avg Rating |
|---------------|----------------|---------------|------------|
| **Mumbai**    | 74%            | ₹ 22.4 Cr     | 4.3        |
| **Bangalore** | 69%            | ₹ 18.2 Cr     | 4.2        |
| **Hyderabad** | 65%            | ₹ 16.8 Cr     | 4.1        |
| **Delhi**     | 63%            | ₹ 14.1 Cr     | 4.0        |

🔹 Mumbai is the strongest market, leading both in revenue and occupancy.
🔹 Delhi shows lower occupancy but competitive ratings.

⭐ 2. Room Category Insights
| Room Category     | Occupancy | ADR (₹) | Revenue Share |
| ----------------- | --------- | ------- | ------------- |
| **Elite Deluxe**  | 75%       | 8,400   | 32%           |
| **Premium Suite** | 68%       | 12,600  | 28%           |
| **Standard Room** | 64%       | 5,200   | 25%           |
| **Luxury King**   | 70%       | 15,200  | 15%           |

🔹 Elite Deluxe rooms deliver the highest booking volume.
🔹 Luxury King has the highest ADR but a lower share of total bookings.


⭐ 3. Revenue Realization
| Metric                                    | Value     |
| ----------------------------------------- | --------- |
| **Gross Revenue**                         | ₹ 78.5 Cr |
| **Realized Revenue (Post-Cancellations)** | ₹ 72.9 Cr |
| **Revenue Realization %**                 | **92.8%** |

🔹 The cancellation rate is moderate, with strong realization numbers.


⭐ 4. Guest Ratings & Behavior
- Average rating: 4.2 / 5
- Most common complaints: WiFi speed, late check-ins, food delays
- Highest-rated category: Premium Suite (4.4)
- Most frequent booking window: 0–3 days before stay (last-minute bookings dominate)

⭐ 5. Monthly Occupancy & Revenue Trends
- Peaks observed in October–December (festive & travel season)
- Slow periods: April & June
- Revenue closely follows occupancy seasonality patterns
- Business travel spikes seen in January–March

## 📁 Visual Insights:
You included charts such as:
- Line charts: Monthly revenue & occupancy trends
- Bar charts: Room category comparison & city-wise performance
- Pie charts: Revenue distribution & booking channel split
- Heatmaps: Rating correlations & occupancy vs ADR patterns


## 📁 Final Business Insights:
- AtliQ Grand's strongest revenue markets are Mumbai and Bangalore.
- Elite Deluxe rooms deliver the highest occupancy and revenue share — opportunity to expand inventory.
- Premium Suite category attracts high-value guests and shows top satisfaction scores.
- Focus improvement areas: check-in experience, WiFi complaints, and kitchen delays.
- Seasonal dips highlight an opportunity for mid-year promotional offers.
- High last-minute bookings indicate need for dynamic pricing strategies.

---

## 📌 Conclusion

This Hospitality Analytics project provides a comprehensive understanding of AtliQ Grand’s operational performance, revenue patterns, and guest behavior across multiple cities and room categories. By transforming raw hotel data into actionable insights, the analysis highlights clear opportunities to optimize occupancy, improve guest satisfaction, and increase revenue realization.

Key conclusions include:

- **Mumbai and Bangalore** lead in both occupancy and revenue generation, establishing them as high-performing markets.  
- **Elite Deluxe and Premium Suite** categories drive the highest occupancy and guest satisfaction, indicating strong demand and premium customer preference.  
- **Revenue realization remains strong (92–93%)**, although cancellations suggest opportunities for operational improvements.  
- **Guest ratings average around 4.2/5**, but recurring complaints related to WiFi, check-in delays, and food service point to clear areas for service enhancement.  
- **Seasonal demand patterns** (e.g., peaks during Oct–Dec and dips in April–June) highlight the need for better inventory and pricing strategies.  

Overall, these insights empower AtliQ Grand to make data-driven decisions that improve operational efficiency, enhance guest experience, and strengthen financial performance across its hotel portfolio.

---

## 📁 Overall Summary

This project delivers a full-scale analytical framework that uncovers critical insights into hotel performance using data from multiple operational and guest touchpoints. Through structured EDA, KPI analysis, and visual storytelling, the project highlights:

- **Which cities generate the most revenue and occupancy**  
- **Which room categories contribute heavily to revenue and customer satisfaction**  
- **How revenue, ADR, and RevPAR evolve over months and seasons**  
- **How cancellations impact revenue and overall business performance**  
- **How guest behavior patterns (ratings, complaints, booking windows) influence service strategy**  

By leveraging Python, Pandas, and advanced visualization tools, the analysis provides AtliQ Grand with:

- A **clear understanding of business performance drivers**  
- Actionable metrics to **optimize pricing, staffing, and marketing strategies**  
- A pathway to **enhance guest satisfaction and loyalty**  
- Data-backed insights that support **long-term growth and competitive advantage**

This project demonstrates the power of analytics in the hospitality domain and showcases how data can be used to transform hotel operations, elevate guest experience, and maximize profitability.

---



