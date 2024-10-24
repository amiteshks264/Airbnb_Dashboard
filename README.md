# Airbnb Booking Analysis
This repository offers a thorough analysis of Airbnb booking data, utilizing Tableau for visualization and Python for data processing. The project's aim is to extract insights from the booking data, examine key trends, and analyze room availability, owner demographics, and budget allocations.

# Project Overview
The project focuses on a detailed analysis of Airbnb bookings with the following objectives:

- **Room Availability Analysis:** Examine the distribution and availability of various room types across regions.
- **Owner Insights:** Investigate property owners' demographics and their budget allocations for listings.
- **Booking Trends:** Visualize key booking trends, including seasonality, peak booking times, and occupancy rates.
- **Visualization with Tableau:** A Tableau Workbook is included to present key visualizations.

# Dataset Description
The dataset comprises:

- **dim_room.csv:** Information on room types, availability, and pricing.
- **dim_owner.csv:** Data on property owners.
- **dim_budget.csv:** Budget details for listed rooms.
- **airbnb.csv:** The primary dataset containing Airbnb booking information.

Python is used to clean, transform, and prepare the data for Tableau.

# Key Features
**Python Scripts:**
- **csv_to_redshift.py:** Loads processed CSV data into AWS Redshift for further analysis.
- **fake_data_generator.py:** Generates synthetic data for testing and analysis.

**Tableau Workbook:**
- **Airbnb Bookings Analysis.twbx:** Contains visualizations and dashboards created in Tableau.

# Usage
- **Data Preparation:** Use the provided Python scripts to clean and load data into your database.
- **Visualization:** Open the Tableau workbook to explore insights such as:
  - Booking trends over time.
  - Room availability by region.
  - Budget analysis for various room types.
- **Further Analysis:** Extend the analysis by updating the Tableau dashboard or modifying the Python scripts for new data processing.

