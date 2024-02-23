The project is made in R-Studio. The result will be a simple markdown file. We aim to analyze renewable energies in the EU. Check how production and consumption change over time for different countries and different resources. How does it influence the price and CO2 emission?

Introduction: We aim to analyze energy consumption, especially renewable energies, and how it changes over the years. We limit our analysis only for EU area, as it has more information about renewable energies than any other area. Our plan is to try to answer the following questions:

Renewable Energy Adoption and Growth

How does it evolve over time?

Can we forecast the future growth in a specific region?

What factors influence the growth?

What are seasonal and annual trends in renewable energy production and how do they impact energy supply and demand?

Electricity price forecasting 1. Can we predict electricity prices based on the availability of renewable energy sources? 2. How does integration impact price volatility?

Carbon emission reduction

How does the growth of renewable energy sources contribute to a reduction in carbon?

Can we estimate the potential impact of future renewable energy adoption on future carbon emissions?

The analysis will be made general for the EU and for each country separately.

Data we need:

Energy consumption for each country annually and monthly for each type of energy production

Electricity prices for each country during the same period

CO2 emissions for each country

1.Obtaining Data

Datasets Our core data covers the following subjects:

-  Electricity generation (TWh), provided both by fuel type and aggregated -  Electricity net imports (TWh) -  Electricity demand (TWh), calculated as the sum of power production and net imports -  Installed power generation capacity (GW), broken down by fuel type -  Emissions from electricity generation (Mt CO2e), calculated from IPCC emissions factors

Fuel Types

In our global dataset, fuel data is mapped into nine generation types: Bioenergy, Coal, Gas, Hydro, Nuclear, Other Fossil, Other Renewables, Solar, and Wind. In our European dataset, Coal is further split into Hard Coal and Lignite.

Overview

Ember releases time series data of power generation, broken down by fuel type, and power imports. These figures are then combined to produce a total power demand time series for each country. "% share" values refer to the share of generation (this does not include net imports) and not the share of consumption unless otherwise specified. We provide data for 215 countries from 2000 to 2021, and where possible have gathered 2022 data using national sources.

Compiling a full dataset from 2000 to 2022 requires using data at multiple timescales. Annual generation data is collected from both national and multi-country sources. For the most recent years, data is often not available. In these cases we use monthly data, which is reported on a shorter lag, to estimate the latest annual generation.

Power data is gathered in a wide variety of formats from multiple sources. In addition to this reconciliation, our data requires considerable cleaning and adjustment of the raw data reported. An overview of our methods is below.
