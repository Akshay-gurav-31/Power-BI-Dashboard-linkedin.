# LinkedIn Profile Dashboard for Akshay Gurav

<p><img src="src/linkedin_dashboard_power_bi.png" alt="LinkedIn Dashboard Preview"></p>

## Overview

LinkedIn is a very powerful social network for communicating and finding a job. In this project, I tried to analyze my profile using the data provided by LinkedIn. This project is not only for analyzing my profile, and anyone who is active in LinkedIn can use this dashboard.

I used [Power BI](https://powerbi.microsoft.com/en/) a great data visualisation tool published by microsoft Power BI provied us great Data trasformation tool to transform our data and easily visualize it.

But before i start, I used at the end i used a little python code to understand better data (optional) :)

## Where to Get LinkedIn Data

Fortunately, LinkedIn has a suitable platform for obtaining information about ourselves. That means there is no scraping :)

Open your LinkedIn -> profile -> setting -> data privacy -> Get a copy of your data

## Project Files

This repository includes the essential files for the LinkedIn dashboard:

- `linkedin dashboard.pbix` - Main Power BI dashboard file for Akshay Gurav
- `preprocessing_data.ipynb` - Jupyter notebook for data cleaning and preprocessing
- `src/` - Directory containing images for the README

## How to Update This Dashboard for Your Profile

### Step 1: Export Your LinkedIn Data
1. Go to your LinkedIn profile
2. Navigate to Settings & Privacy → Data Privacy
3. Click "Get a copy of your data"
4. Download the data package when it's ready

### Step 2: Prepare the Data Using Python
- Run the preprocessing script: `jupyter notebook preprocessing_data.ipynb`
- This will clean and format your raw LinkedIn data
- The notebook creates processed CSV files ready for Power BI

### Step 3: Update the Power BI Dashboard
1. Open `linkedin dashboard.pbix` in Power BI Desktop
2. Go to "Transform Data" → "Data Source Settings"
3. Update the file paths to point to your processed CSV files
4. Click "Refresh" to load your data

### Step 4: Customize for Your Profile
- Replace "Akshay Gurav" with your name in all titles and labels
- Update the color scheme:
  - Primary: #2596be (Blue)
  - Secondary: #4CAF50 (Green)
  - Accent: #FF5722 (Orange)
- Adjust any visualizations to match your data

## Data Preprocessing

The preprocessing script handles:
- Cleaning and formatting raw LinkedIn data exports
- Handling missing values
- Preparing CSV files for Power BI
- Creating processed files with clear column names

To run the preprocessing:
```bash
jupyter notebook preprocessing_data.ipynb
```

## Libraries and packages for python notebook:

- [pandas](https://pandas.pydata.org/)
- [PowerBI](https://www.microsoft.com/en-us/power-platform/products/power-bi)
