# Socio-Economic Effects on COVID-19 Mortality Rates
### A Machine Learning Approach

## 📋 Abstract

This research investigates the relationship between various socio-economic factors and state-level COVID-19 mortality rates across the United States. Using machine learning regression techniques, the study analyzes data collected from 2020-2023 to identify significant correlations between social and economic indicators and population loss due to COVID-19.

## 🎯 Research Objectives

The primary goal of this study is to determine which socio-economic factors most significantly influenced COVID-19 mortality rates at the state level, providing insights that could inform future public health policy and pandemic preparedness.

## 📊 Dataset

Data was collected from reliable government and institutional sources spanning three years (2020-2023):

| **Variable** | **Source** | **Link** |
|-------------|-----------|----------|
| Poverty Rates | USDA Economic Research Service | [View Data](https://data.ers.usda.gov/reports.aspx?ID=17826) |
| State Population | USDA Economic Research Service | [View Data](https://data.ers.usda.gov/reports.aspx?ID=17827) |
| Average State Income | Federal Reserve Economic Data | [View Data](https://fred.stlouisfed.org/release/tables?eid=259515&rid=249) |
| State Health Rankings | Forbes Advisor | [View Data](https://www.forbes.com/advisor/life-insurance/states-ranked-least-healthy-populations/) |
| COVID-19 Deaths | Statista / CDC | [View Data](https://www.statista.com/statistics/1103688/coronavirus-covid19-deaths-us-by-state/) |

### Additional Data Files Included:
- `Provisional_COVID-19_Deaths_by_Place_of_Death_and_State_20240124.csv` - CDC provisional death data
- `State_Populations.csv` - State-level population data
- `Percentage-in-Poverty.csv` - State poverty percentages
- `average-income-by-state-2024.csv` - Income by state
- `united-states-by-density-2024.csv` - Population density metrics
- `h08.xls` - Health insurance coverage data

## 🔬 Methodology

This study employs multiple machine learning regression techniques to analyze the relationship between predictor variables and COVID-19 mortality rates:

- **Least-Squares Regression** - Baseline linear regression model
- **Multiple Least-Squares Regression** - Multi-variable regression analysis
- **Ridge Regression** - L2 regularization to prevent overfitting
- **Lasso Regression** - L1 regularization for feature selection

## 📈 Key Findings

Findings can be found in the research paper attached to this file.

## 🏫 Acknowledgments

This research was conducted as part of the Belmont University SURFS and presented at the 2024 Summer Undergraduate Research Fellowship Symposium (SURFS).

---

**Project Status:** ✅ Completed (Summer 2024)
