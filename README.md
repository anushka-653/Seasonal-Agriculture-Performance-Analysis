# Seasonal-Agriculture-Performance-Analysis

Project Overview

This project analyzes seasonal agricultural performance using data on crops, farms, environmental conditions, resource usage, production, yield, revenue, costs, profit, and disease/pest risk.

The analysis compares Kharif, Rabi, and Zaid seasons to identify differences, patterns, trends, relationships, and variations in agricultural performance.

Objectives

Explore and understand the agricultural dataset.

Clean and prepare the data for analysis.

Compare agricultural performance across seasons.

Analyze yield, production, revenue, cost, and profit.

Examine water usage and water-use efficiency.

Study rainfall and temperature patterns.

Investigate relationships between rainfall, soil moisture, fertilizer usage, and yield.

Analyze disease/pest risk.

Compare crop-wise and state-wise performance.

Identify important patterns and provide recommendations.

Dataset

The dataset contains 28 fields:

Farm_ID, State, District, Crop, Season, Farm_Area_Hectares, Rainfall_mm, Avg_Temperature_C, Humidity_pct, Sunlight_Hours_Day, Soil_pH, Soil_Moisture_pct, Nitrogen_kg_ha, Phosphorus_kg_ha, Potassium_kg_ha, Irrigation_Method, Fertilizer_kg_ha, Pesticide_Litre_ha, Seed_Quality_Score, Yield_Tonnes_Ha, Production_Tonnes, Market_Price_INR_Tonne, Total_Cost_INR, Revenue_INR, Profit_INR, Water_Used_m3, Water_Efficiency_t_per_1000m3, Disease_Pest_Risk_pct

Analysis

The project answers 14 questions covering:

Production distribution across seasons

Average yield by season

Average profit by season

Revenue and cost comparison

Water usage by season

Water-use efficiency

Rainfall and temperature variation

Rainfall vs. yield

Soil moisture vs. yield

Fertilizer usage and yield

Disease/pest risk

Crop performance by season

State-wise seasonal performance

Overall seasonal insights and recommendations

Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

CSV Dataset

Key Findings

Seasonal Performance

Kharif shows the strongest overall performance.

Kharif has the highest average yield, production, profit, and water-use efficiency.

Rabi shows moderate overall performance.

Zaid has the lowest average yield, production, profit, and water-use efficiency.

Environmental & Resource Findings

Kharif has the highest average disease/pest risk.

Soil moisture and yield have an almost negligible linear correlation (approximately 0.010).

Average fertilizer usage differs only slightly between seasons.

Crop Findings

Sugarcane has the highest average yield in all three seasons.

Sugarcane also has the highest average profit in all three seasons.

Chilli is another strong-performing crop.

Several crops show negative average profit in Rabi and Zaid.

State-wise Findings

Seasonal performance differs considerably across states.

Punjab has particularly high average yield in Rabi.

Karnataka performs strongly in Kharif and Zaid.

Maharashtra performs relatively well in Rabi but has much lower average yield in Zaid.

Recommendations

Prioritize crop planning for Kharif while managing its higher disease/pest risk.

Strengthen pest and disease monitoring during Kharif.

Improve irrigation and resource planning for lower-performing seasons, especially Zaid.

Select crops according to both season and location.

Consider profitability along with yield when selecting crops.

Use state-wise seasonal patterns for location-specific planning.

Investigate additional environmental and management factors because soil moisture alone shows almost no linear relationship with yield.

Project Structure

Seasonal Agriculture Performance Analysis/
├── Seasonal Agriculture Performance Analysis(1).ipynb
├── seasonal_agriculture_performance_dataset.csv
└── README.md

How to Run

Install Python and Jupyter Notebook.

Install the required libraries:

pip install pandas numpy matplotlib seaborn jupyter

Keep the notebook and CSV dataset in the same folder.

Open the notebook in Jupyter Notebook.

Run the cells from top to bottom.

Future Scope

Add real-time weather and market-price data.

Develop machine-learning models for yield and profit prediction.

Predict disease and pest risks.

Integrate soil and weather sensor data.

Develop an interactive agricultural dashboard.

Add more years of historical data.

Generate location-specific crop and resource recommendations.

Conclusion

The analysis shows clear differences in agricultural performance across Kharif, Rabi, and Zaid seasons. Kharif demonstrates the strongest overall results, while Zaid requires greater attention to improve yield, profitability, and resource efficiency. Crop-wise and state-wise variations further indicate that agricultural planning should consider both season and location.
