# Cars-data-set-analysis

# 🚗 Cars Data Analysis Project
## 📌 Project Overview
This repository presents a comprehensive Exploratory Data Analysis (EDA) of a cars dataset, aiming to extract insightful patterns useful for predictive modeling, market trend evaluation, and informed automotive decisions.

Dataset Source: Kaggle Cars Dataset

## 📚 Dataset Features
Model: Specific car model

Year: Year of manufacture

Price: Selling price of the car

Transmission: Manual, Automatic, Semi-Auto, etc.

Mileage: Total distance traveled by the car

Fuel Type: Petrol, Diesel, Hybrid, etc.

Tax: Road tax amount

MPG: Miles per gallon (fuel efficiency)

Engine Size: Engine capacity in liters

Manufacturer: Car brand/manufacturer

## 🧹 Data Cleaning Process
Numeric Data: Missing numeric values (price, fuel efficiency, tax, engine size) were handled by averaging data from a 5-year window around the missing year, smoothing economic variations.

Categorical Data: Filled missing transmission and fuel type data using the previous year's data for consistency.

## 📊 Graphical Analysis
Fuel Type Distribution: Pie chart analysis revealed majority Petrol (55.1%), followed by Diesel (41.5%), Hybrid (3.1%), and others.

Transmission Type: Pie chart showed Manual (57%), Semi-Automatic (23%), Automatic (20%), indicating manual transmissions dominate older models.

Price Trends by Year: Line chart illustrated overall price trends, noting a sharp price dip during COVID-19 (2020), followed by recovery.

### Limitation: Line charts of overall data might fail to distinguish between inflationary effects, economic trends, and shifts in popularity or availability of specific car models.

## 💡 Creative Implementation (Advanced Insights)
To overcome limitations in the general price trend analysis, we implemented:

Correlation Matrix: Identified relationships between numeric features; e.g., price and engine size (positive correlation), price and mileage (negative correlation).

Pivot Table Visualization: Created detailed model-specific yearly analyses, examining trends in:

Prices (year-over-year changes)

Fuel Efficiency (km per liter)

Road Tax Amounts

Model Popularity (listing counts)

This deeper analysis helps clearly separate model-specific trends from broader economic influences and provides targeted insights valuable for marketing, competitive strategy, and customer decision-making.

## Participants in the project: 
Nassir Almotairi ,Abdullah Alqurashi, Rayan Majed and Mohammad Saad



