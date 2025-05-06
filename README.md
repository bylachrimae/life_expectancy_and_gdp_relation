# GDP and Life Expectancy Analysis

## Project Overview

This project analyzes the relationship between GDP (Gross Domestic Product) and life expectancy across different countries over several years. The goal is to explore the correlation between economic growth and public health, and investigate whether higher GDP always leads to higher life expectancy. Additionally, we examine instances where GDP growth did not correspond to improved life expectancy, exploring potential reasons behind such discrepancies.

---

## Key Questions Analyzed

1. **Is there a correlation between GDP and life expectancy within each country?**
2. **How does the relationship between GDP and life expectancy differ across countries?**
3. **Does a higher GDP always correspond to higher life expectancy over time?**
4. **What is the impact of GDP growth on life expectancy in years where the economy increased but life expectancy stagnated or declined?**

---

## Project Structure

1. **Data Preprocessing:**
   - Cleaning and transforming raw data for analysis.
   - Handling missing values and irrelevant data.
   - Calculating GDP growth and life expectancy changes.

2. **Exploratory Data Analysis (EDA):**
   - Calculating and visualizing correlations between GDP and life expectancy.
   - Investigating trends and anomalies across countries and years.

3. **Visualizations:**
   - Line plots showing life expectancy over time for each country.
   - Heatmaps to visualize correlations and anomalies.
   - Year-by-year GDP vs life expectancy comparison to observe patterns of stagnation or decline in life expectancy despite GDP growth.

4. **Statistical Analysis:**
   - Calculation of correlation coefficients for each country to evaluate the strength of the relationship between GDP and life expectancy.
   - Insights on discrepancies in countries where GDP increased, but life expectancy remained stagnant or decreased.

---

## Requirements

To run this analysis, you will need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these libraries by running:

```bash
pip install pandas numpy matplotlib seaborn
