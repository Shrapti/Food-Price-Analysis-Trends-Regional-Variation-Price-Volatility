# Food Price Analysis: Trends, Regional Variation & Price Volatility

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of food price data collected across different countries, regions, markets, and commodities.

The objective is to explore food price distributions, understand variations across different dimensions, analyze price patterns over time, and identify meaningful insights using Python.

The analysis includes data cleaning, statistical summaries, outlier detection, visualizations, and pivot tables.

## Objectives

* Analyze food price distributions and identify unusual values.
* Explore food price records across countries and markets.
* Compare recorded prices across different commodities.
* Understand yearly variations in recorded food prices.
* Examine relationships between countries, commodities, and price types.
* Identify patterns and limitations in the available data.

## Tools & Technologies

* **Python** — Data analysis and processing
* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Analysis and documentation

## Dataset

The project uses the `wfp_market_food_prices.csv` dataset containing food price records from different countries and markets.

The dataset includes information such as:

* Country
* Region
* Market
* Commodity
* Currency
* Price type
* Unit of measurement
* Month and year
* Recorded price

**Note:** The dataset contains multiple currencies and measurement units. Therefore, raw prices across different countries and commodities should not be interpreted as directly comparable without appropriate standardization.

## Project Workflow

### 1. Data Loading and Preparation

* Imported the dataset using Pandas.
* Renamed columns for better readability.
* Examined the dataset structure and data types.

### 2. Data Quality Checks

* Checked for missing values.
* Identified duplicate records.
* Examined data types and descriptive statistics.
* Detected potential outliers using the Interquartile Range (IQR) method.
* Identified zero-price records and removed records with prices equal to zero.

### 3. Univariate Analysis

* Examined the distribution of recorded food prices.
* Identified the most frequently recorded commodities.
* Analyzed countries with the highest number of records.
* Explored price type distribution.
* Examined the number of records across different years.

### 4. Bivariate Analysis

* Analyzed yearly average recorded prices.
* Compared recorded prices across frequently observed commodities.
* Examined country-wise average recorded prices.
* Compared average recorded prices across price types.

### 5. Multivariate Analysis

* Examined recorded price patterns across years and countries.
* Compared recorded prices across selected countries and commodities.
* Explored variations across multiple dimensions using visualizations.

### 6. Pivot Table Analysis

* Summarized average recorded prices by year.
* Examined country-wise price type patterns.
* Identified countries with the highest number of food price records.
* Used a heatmap to visualize differences across selected categories.

## Key Insights

The analysis highlighted the following patterns:

1. Food price records cover multiple countries, markets, commodities, and currencies.
2. The recorded price distribution is highly right-skewed, with a relatively small number of high values.
3. The number of observations varies across countries, resulting in unequal data representation.
4. Recorded price patterns differ across commodities and price types.
5. The yearly distribution of records varies, affecting the amount of information available for different periods.
6. Price patterns vary across countries, commodities, and years.
7. The dataset contains multiple currencies and measurement units, which limits direct international price comparisons.

## Visualizations

The notebook includes:

* Food price distribution histogram
* Top commodities by number of records
* Top countries by number of records
* Price type distribution chart
* Year-wise record distribution
* Year-wise average recorded price line chart
* Commodity-wise price comparison
* Country-wise price comparison
* Country and commodity analysis
* Country-wise price type heatmap

## Limitations

* Different currencies prevent direct comparison of raw prices across countries.
* Different measurement units can make commodity price comparisons misleading.
* Unequal record counts across countries may influence overall patterns.
* Outliers may represent genuine market conditions rather than errors.
* The analysis identifies patterns in the available data but does not establish the causes of price changes.

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Missing-value and duplicate checks
* Descriptive statistics
* Outlier detection using IQR
* Data aggregation and pivot tables
* Data visualization
* Analytical interpretation

## How to Run the Project

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the project folder

```bash
cd Food-Price-EDA-Analysis
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Place the dataset

Place `wfp_market_food_prices.csv` in the project directory, or update the notebook's file path to match your dataset location.

### Step 5: Open Jupyter Notebook

```bash
jupyter notebook
```

Open `Food_Price_EDA_Analysis.ipynb` and run the notebook cells in order.

## Conclusion

This project demonstrates how Python-based exploratory data analysis can be used to examine food price records, understand distributions, explore variations across countries and commodities, and investigate patterns over time.

It also highlights the importance of data quality, appropriate comparisons, and careful interpretation when working with real-world datasets.

## Author

**Shrapti Bedre**

Information Technology Graduate | Aspiring Data Analyst

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn

