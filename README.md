# SALURBAL_MS10
Repository for the article _Life expectancy and mortality in 363 cities of Latin America: the SALURBAL project_.
Article available in Nature Medicine at https://www.nature.com/articles/s41591-020-01214-4

**Files:**

* _Data_Management.R_: Contains data management, from SALURBAL harmonized data to data in 5-year age groups, sex, and city, with the list of years for each country, and the distribution of undercounting factors. Contains the code to calculate undercounting factors. Also prepares predictors data and cause-specific mortality data.
* _LE_Estimation.R_: Contains the estimation of life expectancy.
* _Analysis.R_: Contains all analysis for the paper. Also saves data for the online app.
* _MS10_SALURBAL_Helper.R_: Contains a few helper functions.
* _MS10/app.R_: Contains the Shiny app available at https://drexel-uhc.shinyapps.io/MS10/
