# GTA Housing Analysis

The project analyses the change in the housing prices over time in Southern Ontario region. We have also analysed if there is any increase or decrease in the housing prices due to Covid-19 pandemic.

Below are the questions which we want to answer with the help of data:

* How does house price change over time? 
* What are the housing price trends across different regions in Southern Ontario ( 2015 vs 2020) 
* Income per region, and ratio of income to housing price (income / house)
* How has housing prices been affected by COVID-19?

Source of Dataset:

Housing Prices by Year and Area:
CREA - The Canadian Real Estate Association Website
https://creastats.crea.ca/en-CA/

Income by Year and Area:
Canada Revenue Agency Website
https://www.canada.ca/en/revenue-agency/programs/about-canada-revenue-agency-cra/income-statistics-gst-hst-statistics/individual-tax-statistics-area-itsa.html


Data cleaning process involves the following steps:

* Earlier we had dataset with 1124 rows and 8 columns which also had some null values. 
* With little bit cleaning, we removed the null values and left with 1110 rows and 8 columns.
* Renamed the column headers.
* Replaced the “_” from the region’s name.
* Formatted the benchmark price and round it to two decimal places and added a ‘$’ sign to make it more presentable and meaningful.


What do our finding means:

* Significant increase in housing prices over last 5,10, and 15 year periods across all six regions under our coverage for Southern Ontario
* Prices for two-storey increased faster than apartments.
* Multiple factors affected prices, such as steady economic growth, steady influx of new immigrants as well as economic/regulatory factors such as interest decreases in 2008 and 2015 as well as tax levies in 2017.
* Income growth has not been able to match the pace of house price increases. Across all six regions, we have observed the housing price to income ratio increase by nearly 50% from 2010 to 2017.
* Lastly, we try to determine the impact of the coronavirus pandemic on housing prices, if any. We observe that lockdown situation has not impacted prices in any way, in fact, we see that prices have increased at a faster rate in the first five month of 2020 vs the same time period in 2019. We believe that it is likely due to the fact that housing prices are sticky (sellers reluctant to sell in a down market) as well as lag time between listing and actual closing, which would mean that actual data for this period may not yet be available.

