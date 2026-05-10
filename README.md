# Zomato Data Cleaning & Exploratory Data Analysis (EDA) 🍴📊

## 📌 Project Overview
This repository focuses on the end-to-end data preparation and exploratory analysis of the global Zomato restaurant dataset. The goal of this project was to take raw, unrefined data and transform it into a clean, structured format ready for business intelligence and predictive modeling.

## 📂 Datasets
The project utilizes two primary data sources:
* [cite_start]**zomato.csv**: The main dataset containing over 9,500 restaurant listings across 15 countries[cite: 243].
* [cite_start]**Country-Code.xlsx**: A lookup table used to map numerical country codes to their respective country names[cite: 243].

## 🛠️ Data Cleaning Process
To ensure data quality for the EDA, the following steps were performed:
* [cite_start]**Handling Encodings**: Resolved `Latin-1` encoding issues to correctly read the raw restaurant data[cite: 191].
* [cite_start]**Data Integration**: Performed a join between the restaurant dataset and country codes to enable geographical insights[cite: 243].
* [cite_start]**Missing Value Treatment**: Identified and addressed missing values in the `Cuisines` column[cite: 212].
* [cite_start]**Feature Engineering**: Standardized pricing data and created rating categories for better visualization[cite: 286].

## 📊 Exploratory Data Analysis (EDA) Insights
The EDA phase uncovered several key findings:
* [cite_start]**Global Distribution**: Analysis showed that India holds the largest share of restaurants in the dataset, followed by the USA and UAE[cite: 284].
* [cite_start]**Rating Patterns**: Discovered a high concentration of restaurants with "No Rating," which were isolated for deeper investigation into customer engagement[cite: 249].
* [cite_start]**Cost vs. Rating**: Identified the correlation between the "Average Cost for Two" and the final "Aggregate Rating" received by a restaurant[cite: 186, 235].
* [cite_start]**Service Availability**: Measured the impact of offering **Online Delivery** and **Table Booking** on a restaurant's total vote count[cite: 215, 272].

## 💻 Tech Stack
* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
* [cite_start]**Visualization**: Power BI (`Zomato_Insights_Dashboard.pbix`) [cite: 1, 291]

