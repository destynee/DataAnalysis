<!--- # DataAnalysis
Data science and other data analysis projects. -->

## [Analyzing Global Health Trends With WHO Data](https://github.com/destynee/DataAnalysis/blob/main/ExploratoryDataAnalysis.ipynb)  
Investigating the relationship between government health expenditure and women's overall health outcomes across countries with varying GDP levels.

### Research Question
In 2021, what is the relationship between general government health expenditure and women’s overall health across 5 countries with the highest GDP, 5 countries with middle GDP, and 5 countries with the lowest GDP?

### Methodology
**Data Collection**: Compiled international datasets on GDP, government health expenditure, and women’s health indicators (e.g., life expectancy, maternal mortality, access to care).  
**Data Cleaning**: Standardized country-level data, handled missing values, and ensured comparability across metrics.  
**Grouping by GDP**: Classified countries into three tiers (top 5, middle 5, bottom 5 by GDP).  
**Exploratory Statistics**: Calculated averages, variances, and correlations between expenditure and health outcomes.  
**Visualization**: Produced scatterplots, bar charts, and comparative plots to highlight differences across GDP tiers  
**Interpretation**: Assessed whether higher government spending consistently aligned with better women’s health outcomes across economic contexts.

### Key Findings
**High-GDP countries**  
Showed strong investment in health expenditure, generally correlating with higher women’s life expectancy and lower maternal mortality.  

**Middle-GDP countries**  
Displayed mixed results. Moderate spending sometimes translated into significant health improvements, but inconsistencies suggested other structural factors at play.  

**Low-GDP countries**  
Even with proportionally lower spending, some demonstrated notable gains in women’s health, highlighting the importance of efficiency and targeted programs.

**Overall trend**  
A positive relationship exists between government health expenditure and women’s health outcomes, but GDP tier moderates the strength and consistency of this relationship.  

**Data limitations**  
Missing or uneven reporting across countries constrained the scope of conclusions, underscoring the need for more standardized global health data.

## Technologies / Resources
- [GDP (current US$)](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
- [World Health Statistics 2024](https://data.who.int/)
- [Matplotlib](https://github.com/matplotlib/matplotlib)
- [NumPy](https://github.com/numpy/numpy)
- [Pandas](https://github.com/pandas-dev/pandashttps://github.com/pandas-dev/pandas)
- [Seaborn](https://github.com/mwaskom/seaborn)
