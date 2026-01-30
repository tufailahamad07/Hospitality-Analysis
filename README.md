# Hospitality-Analysis
## End-to-end hotel booking data analysis using Python, Pandas, and data visualization
### Project Overview

This project focuses on analyzing hotel booking data to gain insights into:

Occupancy rates

Revenue performance

Customer booking behavior

City-wise and room-wise trends

The analysis is performed using Python, mainly with Pandas for data processing and Matplotlib for visualization.

🎯 Objectives

The main goals of this project are:

Clean and preprocess raw hotel booking data

Remove invalid entries and outliers

Calculate occupancy percentage

Analyze performance by:

Room category

Room class

City

Weekend vs weekday

Monthly revenue trends

📂 Dataset Used

The project uses multiple CSV files:

fact_bookings.csv → Booking transaction data

dim_date.csv → Date information

dim_hotels.csv → Hotel details

dim_rooms.csv → Room categories and classes

fact_aggregated_bookings.csv → Aggregated booking stats

new_data_august.csv → New month data

🛠 Tools & Technologies

Python 🐍

Pandas 📊

Matplotlib 📈

Jupyter Notebook

🔍 Key Analysis Performed
✔ Data Cleaning

Removed bookings with zero or negative guests

Handled missing values

Removed revenue outliers using statistical methods

✔ Occupancy Rate Calculation
Occupancy % = (Successful Bookings / Capacity) × 100

✔ Insights Generated

Average occupancy by room category

Average occupancy by room class

City-wise occupancy rate

Weekend vs weekday comparison

June month city-wise performance

Revenue realized per city

Month-by-month revenue trend

📊 Sample Insights

Certain room classes show higher occupancy

Weekends generally have better occupancy

Some cities generate higher revenue consistently

Monthly revenue trends help identify growth periods

📈 Visualizations

The project includes bar charts to represent:

Booking platform usage

City-wise occupancy

Monthly revenue comparison

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/hotel-analysis.git


Install required libraries

pip install pandas matplotlib


Open Jupyter Notebook

jupyter notebook


Run hotel_analysis.ipynb

📌 Project Structure
📁 datasets/
   ├── fact_bookings.csv
   ├── dim_date.csv
   ├── dim_hotels.csv
   ├── dim_rooms.csv
   ├── fact_aggregated_bookings.csv
   └── new_data_august.csv

📄 hotel_analysis.ipynb
📄 README.md

✅ Conclusion

This project demonstrates:

Real-world data cleaning techniques

Data merging using multiple tables

Business insights generation

Visualization for decision making

It is useful for understanding hotel performance and improving business strategies.
