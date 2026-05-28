# Exploratory Data Analysis (EDA) Project

A Python-based Exploratory Data Analysis (EDA) project focused on analyzing raw cafe sales data to uncover patterns, trends, correlations, and meaningful business insights using statistical analysis and data visualization techniques.

---

## Project Overview

This project performs detailed Exploratory Data Analysis (EDA) on a messy cafe sales dataset containing:
- Missing values
- Invalid entries
- Mixed data types
- Categorical and numerical variables

The objective is to clean, analyze, and visualize the dataset to identify trends, correlations, and key influencing factors that affect cafe sales.

---

## Features

- Data Cleaning & Preprocessing
- Statistical Summaries
- Missing Value Analysis
- Correlation Analysis
- Trend Identification
- Data Visualization
- Business Insight Generation
- Pattern Recognition
- Exploratory Analysis using Graphs and Charts

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## Dataset

Dataset used:
- dirty_cafe_sales.csv

### Dataset Columns
- Transaction ID
- Item
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

---

## Objectives of the Project

- Understand the structure of the dataset
- Identify missing and inconsistent data
- Analyze relationships between variables
- Discover trends and patterns
- Generate business insights using visual analytics

---

## Data Preprocessing Steps

### 1. Handling Missing Values
- Filled missing numerical values
- Filled missing categorical values

### 2. Removing Invalid Entries
Replaced invalid entries such as:
- ERROR
- UNKNOWN

with null values for proper processing.

### 3. Data Type Conversion
Converted numerical columns into proper numeric format.

### 4. Duplicate Removal
Removed duplicate records to improve dataset quality.

### 5. Date Processing
Converted transaction dates into datetime format for time-series analysis.

---

## Exploratory Data Analysis (EDA)

### Statistical Summary
Generated descriptive statistics including:
- Mean
- Median
- Standard Deviation
- Minimum & Maximum Values

### Correlation Analysis
Analyzed relationships between numerical variables using correlation matrices and heatmaps.

### Trend Analysis
Observed sales patterns across:
- Dates
- Product categories
- Payment methods
- Locations

---

## Visualizations Included

### 1. Most Sold Items
Bar chart showing top-selling products.

### 2. Revenue by Item
Displays which items generate the highest revenue.

### 3. Payment Method Distribution
Pie chart representing customer payment preferences.

### 4. Correlation Heatmap
Shows relationships between numerical features.

### 5. Daily Sales Trend
Line graph showing sales changes over time.

### 6. Distribution Plots
Analyzed data spread and frequency distribution.

---

## Sample Workflow

text Raw Dataset      ↓ Data Cleaning      ↓ Handling Missing Values      ↓ Data Transformation      ↓ Exploratory Data Analysis      ↓ Visualization      ↓ Pattern & Trend Discovery      ↓ Business Insights 

---

## Key Insights Generated

Some insights identified from the dataset:
- Most frequently purchased cafe items
- Revenue-generating products
- Popular payment methods
- Customer purchase trends
- Relationship between quantity and spending
- Daily and monthly sales patterns

---

## How to Run the Project

### 1. Clone the Repository

bash git clone https://github.com/Sindhuganji/EDA-Project.git 

### 2. Navigate to Project Folder

bash cd EDA-Project 

### 3. Install Required Libraries

bash pip install pandas numpy matplotlib seaborn 

### 4. Run the Python File

bash python exploratory_data_analysis.py 

---

## Learning Outcomes

Through this project, I learned:
- Real-world data preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis techniques
- Data visualization methods
- Analytical thinking
- Data storytelling and insight generation

---

## Future Improvements

- Interactive dashboards using Streamlit
- Power BI integration
- Advanced statistical analysis
- Real-time analytics dashboard
- Automated reporting system

---

## Author

### Pushpa Sri Sindhu
- BTech CSE, SRM AP University
- BS Data Science and Applications, IIT Madras

GitHub:
https://github.com/Sindhuganji

---

## License

This project is open-source and available for educational and learning purposes.
