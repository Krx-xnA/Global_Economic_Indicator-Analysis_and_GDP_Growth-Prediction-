# Global Economic Trends Analysis using World Bank Data

## Project Overview

This project explores global economic trends using datasets collected from the World Bank database. The objective of the analysis was to understand how different economic and social indicators interact with GDP growth across countries and over time.

The project combines multiple datasets, including GDP growth, inflation, unemployment, trade openness, population growth, CO2 emissions, school enrollment, and foreign direct investment (FDI) into a single unified dataset for exploratory data analysis (EDA).

Rather than focusing only on visualizations, the project emphasizes economic interpretation and comparative analysis across countries from different regions of the world.

---

## Objectives

The main goals of this project were:

* Perform data cleaning and preprocessing on multiple World Bank datasets
* Merge different economic indicators into a single dataset
* Analyze relationships between economic variables
* Identify trends, correlations, and outliers
* Compare economic performance across countries
* Build country-wise economic profiles 
* Extract meaningful economic insights from the data

---

## Datasets Used

The following indicators were collected from the World Bank database:

* GDP Growth
* Inflation
* Unemployment Rate
* Trade 
* Population Growth
* CO2 Emissions
* School Enrollment
* Foreign Direct Investment (FDI)

Each dataset was cleaned individually before being merged using common keys:

* Country
* Country Code
* Year

---

## Countries Analyzed

To create a global comparative analysis, countries from different regions were selected:

* United States
* Brazil
* France
* South Africa
* India
* China
* United Arab Emirates
* Australia
* Japan
* United Kingdom

This allowed comparison between:

* developed economies
* emerging economies
* industrialized nations
* resource-driven economies

---

## Tools & Libraries Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Analysis Performed

### Data Cleaning

* Removed unnecessary columns
* Renamed columns for consistency
* Checked for duplicates and missing values
* Standardized dataset structure across all indicators

### Data Merging

* Combined all datasets into a single dataframe using:

  * Country
  * Country Code
  * Year

### Exploratory Data Analysis

* Histograms
* Boxplots
* Scatterplots
* Correlation heatmaps
* Time-series trend analysis
* Cross-country comparison analysis

### Country Economic Profiles

Time-series analysis was performed for multiple countries to study:

* GDP growth trends
* Inflation patterns
* Trade openness
* CO2 emissions
* Foreign investment trends
* Education indicators

---

## Key Insights

### GDP Growth showed a weak correlation with most individual variables

Economic growth appeared to depend on multiple interconnected factors rather than a single dominant indicator.

### Trade openness showed a negative relationship with unemployment

Countries with higher trade integration often exhibited relatively lower unemployment levels.

### Developed economies showed high education enrollment but slower GDP growth

Countries with strong educational systems often displayed stable but mature economic growth patterns.

### Industrialized economies showed higher CO2 emissions

Economic development and industrial expansion appeared to be associated with increased environmental impact.

### Emerging economies demonstrated stronger long-term growth trends

Countries such as India and China showed significantly stronger GDP growth compared to mature economies like Japan.

---

## Project Structure

```
world-bank-eda-project/
│
├── Global_Macroeconomic_EDA.ipynb
├── README.md
├── datasets/
└── images/
```

---

## Future Improvements

Potential future additions to the project include:

* Machine learning models to predict GDP growth
* Country clustering using unsupervised learning
* Geographic visualizations using maps
* Statistical hypothesis testing

---

## Conclusion

This project demonstrates how economic indicators can be combined and analyzed to better understand global economic behavior. The analysis highlights the complexity of economic growth and shows how various factors interact across countries and regions.

The project also served as hands-on practice for:

* data cleaning
* data merging
* exploratory data analysis
* visualization
* storytelling with data

---

## Author

Created as a data analytics and exploratory data analysis project using World Bank datasets.
