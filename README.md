# business_relationships
## Cross-sectoral relationships in business entry dynamics around a highway corridor

#### This repository contains the code and data related files for the paper mentioned above. Codes are used with Python 3.7.

#### Code Files:

##### Modelling codes:

___Spatial Yearly Regression-20 Groups.ipynb__ - This contains the first implemented model - the Spatial Durbin Model. Along with Spatial Durbin, it also contains, Spatial autoregressive model, lagged-X model, and OLS model.

__Network PLS-sp.ipynb__ - This model contains the Partial least squares regression model, used for estimating the network finally.

##### Data analysis and cleaning related codes:



#### Data files:

__20_zvar2.csv__ contains data of population-related variables for each ZCTA across each year (1990, 2000, 2010 - census and others using SAHSU approach). The variables are lagged by 1 year, as mentioned in the manuscript.
__20_zvar3.csv__ contains data of other variables (unemployment rate, education-related, number of airports accommodated, land area, median house price, median income, home ownership). The variables are lagged by 1 year, as mentioned in the manuscript.
__20_zvar4.csv__ contains data of average wage for each sector, ZCTA, and year.

__20_var2.csv, 20_var3.csv, 20_var4.csv__ : These files represent same variables as __20_zvar2.csv, 20_zvar3.csv and 20_zvar4.csv__ respectively on a county level. This is used in SAHSU approach.
