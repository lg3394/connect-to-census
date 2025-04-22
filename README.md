## Income and Health: Exploring the Relationship Between Household Income and Physical Health
This project investigates the connection between median household income and physical health outcomes across U.S. counties, using data from the U.S. Census Bureau and County Health Rankings.

### Project Overview
The analysis explores how economic factors shape health outcomes by examining the relationship between county-level median household income and the average number of physically unhealthy days reported per month.

### Data Sources

Census Dataset: Income in the Past 12 Months (in 2022 inflation-adjusted dollars) at the county level from the U.S. Census Bureau API
Health Dataset: County Health Rankings and Roadmaps' "Poor Physical Health Days" metric, which measures the average number of physically unhealthy days reported in the past 30 days (age-adjusted)

### Key Findings

A strong, non-linear relationship exists between income and health outcomes
Income alone explains over 48% of the variation in unhealthy days across counties
The relationship is stronger in lower-income states, where each $1,000 increase in median income corresponds to a larger decrease in unhealthy days
State-specific factors substantially influence health outcomes beyond income

### Repository Contents

distributions.ipynb: Analysis of income and health distributions
scatterplots.ipynb: Visual exploration of relationships between variables
linear-regression.ipynb: Statistical analysis of income-health relationships
Data collection and processing scripts

### Tools & Methods

R for statistical analysis
Census API for demographic data
Linear regression and t-tests
Log transformations to explore non-linear relationships
Data visualization

### Next Steps
Future work could explore:
    - Additional variables like healthcare access and employment type
    - Outlier counties that deviate from observed trends
    - Non-linear dynamics and potential threshold effects
    - Data quality and cross-state comparability issues
