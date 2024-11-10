# Renewable Energy Analysis in the EU

This project aims to analyze renewable energy production, consumption, and its effects on electricity prices and CO2 emissions in the European Union. We explore the evolution of renewable energy adoption over time, its impact on electricity prices, and how it contributes to reducing carbon emissions.

The analysis is carried out using R-Studio, and the results will be documented in a simple markdown file. The dataset includes time series data for multiple countries, from 2000 to 2021, with projections for 2022, focusing on renewable energy sources, electricity prices, and carbon emissions.

## Project Objectives

The main objectives of this project are:

### 1. Renewable Energy Adoption and Growth
- Analyze how renewable energy adoption evolves over time.
- Forecast the future growth of renewable energy adoption in specific regions.
- Identify the factors that influence the growth of renewable energy sources.
- Examine seasonal and annual trends in renewable energy production and their impact on energy supply and demand.

### 2. Electricity Price Forecasting
- Explore if we can predict electricity prices based on renewable energy availability.
- Study how renewable energy integration impacts price volatility.

### 3. Carbon Emission Reduction
- Investigate how the growth of renewable energy sources contributes to carbon emission reductions.
- Estimate the potential impact of future renewable energy adoption on future carbon emissions.

## Data Sources

The project utilizes several datasets for analysis:

- **Energy Consumption Data**: Includes annual and monthly energy consumption data for each country, broken down by energy production type.
- **Electricity Prices**: Historical electricity prices for each EU country during the study period.
- **CO2 Emissions Data**: CO2 emissions data for each country, correlated with energy production.

The core data covers the following:

- **Electricity generation (TWh)**: By fuel type and aggregated.
- **Electricity net imports (TWh)**.
- **Electricity demand (TWh)**: Sum of power production and net imports.
- **Installed power generation capacity (GW)**: Broken down by fuel type.
- **Emissions from electricity generation (Mt CO2e)**: Calculated from IPCC emissions factors.

### Fuel Types in the Dataset
The dataset classifies fuel data into nine generation types:
- Bioenergy
- Coal (further split into Hard Coal and Lignite)
- Gas
- Hydro
- Nuclear
- Other Fossil
- Other Renewables
- Solar
- Wind

### Data Overview
The data is sourced from Ember, which releases time series data for power generation by fuel type and power imports. This data is collected from both national and multi-country sources and includes:
- Data from **2000 to 2021** for 215 countries.
- **2022 data** sourced from national sources where available.
- The dataset contains values broken down by generation type and net imports.

### Data Cleaning and Preprocessing
The dataset requires significant data cleaning and adjustment, as raw data is provided in various formats. We use both **annual** and **monthly** data to build a complete dataset from 2000 to 2022, filling in gaps where necessary.

## How to Use the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shararezr/Time-Series-Analysis.git
   cd Time-Series-Analysis
