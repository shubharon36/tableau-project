# Tableau: Global Development & Public Health Explorer

## Project Overview

This project is an interactive data exploration tool built in Tableau that analyzes global public health outcomes alongside key socio-economic development indicators. The dashboard integrates pandemic data (Case Fatality Rate, recovery rates, weekly case growth) with metrics from the World Development Indicators dataset (GDP, life expectancy, literacy, etc.). The goal is to identify trends, correlations, and regional disparities to inform public policy and research.


## Key Questions Addressed

1.  Which countries and WHO regions have the highest pandemic-related Case Fatality Rates (CFR)?
2.  Which nations are facing the most critical, rapidly accelerating outbreaks?
3.  What is the relationship between a country's economic status (GDP per Capita) and health outcomes (Life Expectancy)?
4.  How do factors like literacy and urbanization correlate with development indicators like internet usage and emissions?

## Data Sources

* COVID-19 Pandemic Dataset (aggregated by country)
* World Development Indicators Dataset (focusing on GDP, Population, CO2 Emissions, Life Expectancy, Literacy, and Internet Users).

## Methodology & Visualizations

### 1. Geospatial Analysis

* **Choropleth Maps** were used to visualize pandemic metrics globally, such as Case Fatality Rate (CFR), recovery rates, and weekly case increases.
* **Advanced Filtering** was implemented to create a "critical outbreak" map, highlighting countries that met two criteria simultaneously: >1,000 active cases AND >25% weekly increase, effectively identifying high-risk nations.
* **Quadrant Analysis** was used to categorize countries into segments like "Stable Hotspots" (high active cases, low increase) to inform different management strategies. The US, Brazil, and India were identified in this quadrant.

### 2. Correlation Analysis

* **Scatter Plots** were used to explore relationships between development indicators. Key findings include a clear positive relationship between GDP per Capita and Life Expectancy, and between Literacy Rate and Internet Use.
* A **Correlation Matrix** was built to provide a high-level summary of the relationships between all six key development indicators.

## Key Insights & Recommendations

* **Insight**: The European and American WHO regions exhibit the highest median CFRs (3.86% and 2.58% respectively).
* **Recommendation**: Conduct cross-regional studies to understand systemic differences in healthcare infrastructure and policies that led to better outcomes in other regions.
* **Insight**: A strong positive correlation exists between a country's literacy rate and its internet penetration, suggesting literacy is a key enabler of digital adoption.
    * **Recommendation**: Development policies aimed at increasing digital access should be paired with investments in foundational education and literacy.
* **Insight**: Larger populations generally correspond to higher total greenhouse gas emissions, but outliers exist. The U.S. emits more relative to its population, while India emits less.
    * **Recommendation**: Policy should focus not just on population size but on the efficiency and emission standards of high-outlier nations.
