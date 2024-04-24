# SC1015 Mini Project: Predicting Renewable Energy Growth

## Project Motivation
Our project is driven by the urgent issue of climate change. Our goal is to predict the percentage of clean energy in the overall composition of electricity generation by 2050.

## Problem Definition
We aim to estimate the future composition of electricity generation, focusing on the increase in renewable energy sources.

## Exploratory Data Analysis (EDA)
- Tool Used: Heatmap to identify variables strongly related to renewable energy.
- Data Sources: Our data was sourced from various credible databases which track energy usage and generation statistics globally.

## Machine Learning Implementation
- Initial Methods: Non-linear regression and random forest.
  - Faced issues with static future variables due to data leakage from historical dependencies.
- Optimization: Utilized time series analysis with the Prophet library to better predict future trends.
- Reason for Optimization: Initial methods did not fit well; hence the switch to time series to improve prediction reliability.

## Results
Predictions indicate that without significant advancements in clean energy technology and policy, renewable energy use will likely stagnate, resulting in continued reliance on fossil fuels.

## Insights
The stagnation in renewable energy growth can be attributed to the current technological limitations and inadequate policy frameworks that fail to support sustainable energy growth sufficiently.

## Team Contributions
- Zhang Yichi: Led the EDA and ML implementation, defined the problem statement, managed overall project tasks, and designed presentation slides.
- Yan Zhi Xiang: Assisted significantly in defining the problem, selecting datasets, scriptwriting, polishing content, and creating presentation materials.

## References
- [Our World in Data - General Energy Statistics](https://ourworldindata.org/)
- [IEA Clean Energy Database](https://www.iea.org/data-and-statistics/data-tools/clean-energy-demonstration-projects-database)
- [UN Renewable Energy Hub](https://www.un.org/en/climatechange/raising-ambition/renewable-energy)
- [Prophet Library for Time Series Forecasting](https://pypi.org/project/prophet/)
