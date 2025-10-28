# Uber-Rides-Exploration
📊 Project Overview
This project is an Exploratory Data Analysis (EDA) of Uber ride data using Python and popular data science libraries. The analysis focuses on understanding ride patterns, such as the purpose of trips, categories (Business/Personal), and the influence of time and day on ride distribution.

📁 File Structure
The main files in this repository are:

Uber Data Analysis.ipynb: The Jupyter Notebook containing all the data cleaning, feature engineering, analysis, and visualization code.

UberDataset.csv: The primary dataset used for this analysis. Note: You must include this CSV file in your repository for the notebook to run correctly.

✨ Key Analysis & Features
The Jupyter Notebook performs the following key tasks:

Data Cleaning & Preprocessing: Handled missing values, specifically in the PURPOSE column.

Feature Engineering: Created new time-based columns like data (date), time (hour), and day-night (categorizing rides into Morning, Afternoon, Evening, and Night) from the ride timestamps.

Trip Categorization: Analyzed the distribution of trips between Business and Personal categories.

Purpose Analysis: Explored the most common purposes for the recorded rides (e.g., Meal/Entertain, Meeting, Errand/Supplies).

Time Series Analysis: Visualized ride frequency based on the time of day (day-night category).

Distance Analysis: Examined the distribution of miles covered and identified the longest trips.
