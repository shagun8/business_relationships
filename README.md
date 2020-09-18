# business_relationships
Cross-sectoral relationships in business entry dynamics around a highway corridor

This repository contains the code files (modelling related). Codes are used with Python 3.7.

Spatial Yearly Regression-20 Groups.ipynb - This contains the first implemented model - the Spatial Durbin Model. Along with Spatial Durbin, it also contains, Spatial autoregressive model, lagged-X model, and OLS model.

Network PLS-sp.ipynb - This model contains the Partial least squares regression model, used for estimating the network finally.

Data files:

20_zvar2 contains data of population-related variables for each ZCTA across each year (1990, 2000, 2010 - census and others using SAHSU approach). The variables are lagged by 1 year, as mentioned in the manuscript.
20_zvar3 contains data of other variables (unemployment rate, education-related, number of airports accommodated, land area, median house price, median income, home ownership). The variables are lagged by 1 year, as mentioned in the manuscript.
20_zvar4 contains data of average wage for each sector, ZCTA, and year.
