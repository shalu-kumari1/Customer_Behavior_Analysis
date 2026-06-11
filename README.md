# Customer_Behavior_Analysis
## Data Analytics Project

## Overview

This project demonstrates an end-to-end Data Analytics workflow, starting from raw data processing to business insights visualization. The project involves data loading, cleaning, exploratory data analysis (EDA), SQL-based analysis, dashboard creation, and reporting to support data-driven decision-making.

## Dataset

The dataset contains information related to customer transactions, purchasing behavior, and sales trends.

### Key Features

* Customer Details
* Product Information
* Purchase History
* Sales Metrics
* Transaction Records

## Tools & Technologies Used

### Python

* Pandas
* NumPy

### Database

* MySQL

### Business Intelligence

* Power BI


## Project Workflow

### 1. Data Loading

* Imported the dataset using Python.
* Examined dataset structure, dimensions, and data types.

### 2. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Corrected inconsistent data formats.
* Performed data type conversions where necessary.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer behavior and sales patterns.
* Identified trends and key performance indicators.
* Created visualizations to uncover insights.

### 4. SQL Analysis

* Loaded the cleaned dataset into MySQL.
* Wrote SQL queries to:

  * Aggregate sales data
  * Analyze customer purchasing behavior
  * Calculate business metrics
  * Generate summary reports

### 5. Power BI Dashboard Development

* Connected Power BI to the processed dataset.
* Built interactive dashboards and visual reports.
* Added filters, slicers, KPIs, and charts for better analysis.
  

## Dashboard Highlights

The Power BI dashboard includes:

* Sales Performance Overview
* Customer Segmentation Analysis
* Product Performance Tracking
* Revenue and Profit Trends
* Interactive Filters and Slicers
* Key Business KPIs

## Key Results

* Identified major sales trends and customer purchasing patterns.
* Highlighted top-performing products and categories.
* Provided actionable insights to improve business performance.
* Created an interactive dashboard for data-driven decision-making.

---

## Project Structure

```text
Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   ├── data_cleaning.ipynb
│   └── eda_analysis.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
└── README.md
```

---

## How to Run

### Step 1: Clone the Repository

```bash
git clone <repository-link>
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

### Step 3: Run Python Analysis

```bash
jupyter notebook
```

Open and execute the notebooks for data cleaning and EDA.

### Step 4: Load Data into MySQL

* Create a MySQL database.
* Import the cleaned dataset.
* Execute the SQL scripts available in the SQL folder.

### Step 5: Open Power BI Dashboard

* Open the `.pbix` file in Power BI Desktop.
* Refresh the data connection if required.

### Step 6: Review Report and Presentation

* Open the project report for detailed findings.
* Review the presentation for a summary of insights and recommendations.

---

## Conclusion

This project demonstrates the complete Data Analytics lifecycle, including data preparation, analysis, SQL querying, visualization, and business reporting. The generated insights help stakeholders make informed decisions based on data.
