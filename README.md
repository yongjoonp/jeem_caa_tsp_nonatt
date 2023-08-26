# About Repository

This repository contains key the essential datasets used for the analysis presented in the paper authored by Maureen Cropper, Nicholas Muller, Yongjoon Park, and Victoria Perez-Zetune, published in Journal of Environmental Economics and Management (2023), titled ["The impact of the clean air act on particulate matter in the 1970s."](https://doi.org/10.1016/j.jeem.2023.102867)



# Description of the data

There are two folders in this repository --- `data` and `us_aqcr_shape`

## data

In this folder, there are three csv files.

### 1. tsp_nonatt_status_county_level.csv

The dataset includes county-level non-attainment status data for Total Suspended Particulates (TSP) for the years between 1969 and 1978. The descriptions of the variables are provided below:

- `year`: year
- `AQCR`: unique Air Quality Control Regions id
- `fips`: county FIPS code
- `State`: state name
- `tsp_neds`: 1 if county is out of attainment, 0 if it is in attainment under the offical AQCR designation
- `tsp_imputed`: 1 if county is out of attainment, 0 if it is in attainment under the imputed defitnion
- `tsp_arithmetic_mean`: annual average TSP levels
> 

### 2. tsp_nonatt_status_aqcr_level.csv

The dataset includes aqcr-level (Air Quality Control Regions) non-attainment status data for Total Suspended Particulates (TSP) for the year 1972 and 1976. The descriptions of the variables are provided below:

- `AQCR`: unique Air Quality Control Regions id
- `year`: year 
- `att0_nonatt1`: 1 if county is out of attainment, 0 if it is in attainment under the offical AQCR designation


### 3. county_characteristics.csv

The dataset comprises data on annual economic conditions at the county level spanning the years from 1969 to 1980. The descriptions of the variables are provided below:


- `year`: year
- `fips`: county FIPS code
- `population`: population (unit: 1,000)
- `per_income`: per capita income
- `employment_total`: number of employments (unit: 1,000)


## us_aqcr_shape

This folder contains the shape files necessary for mapping the AQCR (Air Quality Control Region) regions.
