# Economic_Imbalance-Python
The Growing Divide between Housing Affordability and Wage Stagnation in the United States 

# Summary
As affordable housing disappears there is concern for the long-term economic sustainability and social fabric of American society. Many Americans face crushing debt and lack of stability, leaving the American Dream of home ownership forever out of reach.
This analysis looks at Median Income, Median House Cost, and Minimum Wage across the United States from 2008-2022.

# Key Questions and Objectives
1) Is the average cost of houses in the US increasing at a greater rate than the average household income from 2008-2022?
2) Is the average cost of houses in the US increasing at a greater rate than the average Minimum Wage from 2008-2022?
3) Find States that are the most expensive to live in by house cost.
4) Find States that are the least expensive to live in by house cost.
5) Find States that have the highest median income.
6) Find States that have the lowest median income.
7) Find States with the best purchasing power where income is more likely to afford a house.
8) Find States with the worst purchasing power where income is least likely to afford a house.

# Context
Purchasing a home in the United States is become more difficult as wages fail to keep up with economic growth. This project will allow future home buyers to see how difficult this idea may be, as well as where to buy.


# Data Sets
All Raw Datasets uploaded to Data/Original. Datasets include:
### Original:
1) [Median_House_Price_By_State] = Zillow (https://www.zillow.com/research/data/), Median House price by state from 2008-2023 
2) [Median_Income_By_State] = US Census Bureau (https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-incomehouseholds.html), Median household income by state from 1984-2022
3) [Minimum_Wage_Data] = United States Department of Labor (http://www.kaggle.com/datasets/lislejoem/us-minimum-wage-by-state-from-1968-to-2017), State and Federal Minimum Wage from 1968-2020
### Prepped:
[Clustering_Integer_Dataset]
[Geospatial_Complete_Data]
[House_Cleaned]
[Income_Cleaned]
[Merged_3_Data]
[Wage_Cleaned]


# Data Cleaning
					
	Dataset	Missing values	Missing values treatment	Duplicates	
	Median_Income_By_State	none	NA	none	
	Median_House_Price_By_State	Several states had missing values for certain areas/cities.	Calculated average of other areas within the state during the same year for a calculated estimate.	none (Except the values that were previously missing and calculated as the average).	
	Minimum_Wage_Data	Several States had missing values for state minimum wage.	Any state with missing values had the federal minimum wage entered.	Several, but to be expected since many states have the same minimum wage.	
	us_states.json	none	NA	none	
					
					
					
![image](https://github.com/KaCeeUnruh/Economic_Imbalance-Python/assets/130774051/65ab20e3-c0b0-4a12-937a-b0ac408f5024)



# Project Links
Tableau: (https://public.tableau.com/views/EconomicImbalance-HousingAffordabilityintheUS/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
