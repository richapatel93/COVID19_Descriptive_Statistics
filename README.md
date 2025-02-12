# COVID-19 Descriptive Statistics and EDA

## Overview
This project involves the analysis of the latest COVID-19 India state-wise data to explore key metrics, such as **Active Cases**, **Discharged Cases**, and **Death Ratios**. Using **Descriptive Statistics** and **Exploratory Data Analysis (EDA)**, this project identifies patterns and trends, and makes recommendations for healthcare management.

The dataset includes attributes such as:
- `State/UTs`: Names of Indian States and Union Territories.
- `Total Cases`: Total number of confirmed cases.
- `Active`: Total number of active cases.
- `Discharged`: Total number of discharged cases.
- `Deaths`: Total number of deaths.
- `Active Ratio (%)`: Ratio of active cases to total cases.
- `Discharge Ratio (%)`: Ratio of discharged cases to total cases.
- `Death Ratio (%)`: Ratio of deaths to total cases.
- `Population`: Population of the State/UT.

## Key Insights
- **Top States with Highest Death Ratios**: States like **Punjab** and **Nagaland** have higher death ratios, indicating potential healthcare challenges.
- **Clusters of States**: Using **K-Means clustering**, we identify states with similar COVID-19 characteristics (Active Cases, Death Ratios, Discharge Rates).
- **Hypothesis Testing**: We tested the hypothesis that states with **higher populations** tend to have **more COVID-19 cases**, and found no significant correlation between the two.

## Objectives
- Perform **descriptive statistics** to summarize the dataset.
- Identify **key trends** and **patterns** in COVID-19 data across Indian states.
- Visualize data using **bar charts**, **scatter plots**, **box plots**, and **heatmaps**.
- Perform **advanced analysis** such as outlier detection, clustering, and hypothesis testing.
- Provide **data-driven insights** and **recommendations** for policymakers.

## Project Goals:
1. **Data Cleaning & Preprocessing**: Handle missing values, detect duplicates, and ensure correct data types.
2. **Descriptive Statistics**: Generate summary statistics for key metrics.
3. **Data Visualization**: Use **histograms**, **bar charts**, **box plots**, and **scatter plots** for visual insights.
4. **Advanced Analytics**: 
   - **Outlier Detection** using **Z-scores**
   - **K-Means Clustering** to find patterns in Active, Discharge, and Death Ratios
   - **Hypothesis Testing** using **t-tests**

## Technologies Used:
- **Python** 🐍
- **Pandas** 📊
- **Matplotlib** 🎨
- **Seaborn** 📈
- **Scikit-learn** 🔧
- **SciPy** 🔬

## How to Run:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/COVID19_Descriptive_Statistics.git


## Dataset:
The dataset used in this project contains **COVID-19 India state-wise data** as of **September 12, 2023**. It includes key information such as the **total number of cases**, **active cases**, **discharged cases**, **deaths**, and the **population** of each Indian state and union territory.

- **Source**: [MyGov COVID-19 Data](https://www.mygov.in/covid-19)
- **Dataset columns include**:
  - `State/UTs`: Names of Indian States and Union Territories.
  - `Total Cases`: Total number of confirmed cases.
  - `Active`: Total number of active cases.
  - `Discharged`: Total number of discharged cases.
  - `Deaths`: Total number of deaths.
  - `Active Ratio (%)`: Ratio of active cases to total cases.
  - `Discharge Ratio (%)`: Ratio of discharged cases to total cases.
  - `Death Ratio (%)`: Ratio of deaths to total cases.
  - `Population`: Population of the State/UT.

The dataset is publicly available and updated periodically.
