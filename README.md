# COVID-19 Data Exploration Project

This project focuses on analyzing global COVID-19 data to derive insights into the pandemic's spread, infection rates, death rates, and vaccination coverage. The SQL queries are used to manipulate and analyze the data from two primary tables: CovidDeaths and CovidVaccinations. Various SQL techniques, such as joins, common table expressions (CTEs), temporary tables, window functions, and aggregate functions, are employed to explore the data in detail.

## Skills Utilized
- Joins: To combine data from multiple tables (CovidDeaths and CovidVaccinations).
- CTEs (Common Table Expressions): For improved readability and reusable calculations.
- Temporary Tables: To store intermediate results for further analysis.
- Window Functions: For running totals and cumulative calculations (e.g., rolling vaccination numbers).
- Aggregate Functions: To calculate metrics like total cases, deaths, and vaccination rates.
- Views: To store query results for future visualizations.
- Data Type Conversion: To ensure consistency when calculating percentages and other numeric data.

## Key Analyses
1. Global Cases and Deaths: Calculated the likelihood of death for COVID-19 cases across different countries and continents.
2. Infection Rates by Population: Determined the percentage of the population infected in each country.
3. Countries with the Highest Infection and Death Rates: Identified which countries have the highest infection and death rates per population.
4. Continent-Level Breakdown: Aggregated data to show the continents with the highest death rates.
5. Vaccination Progress: Calculated the percentage of the population that has received at least one dose of the vaccine, using rolling sums and window functions.

## Data Sources
- CovidDeaths: Contains information about COVID-19 cases, deaths, and population data.
- CovidVaccinations: Contains information about COVID-19 vaccination progress.
