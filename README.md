## Group4_project

# Project Title: Compare Housing Market "Hotness": Dallas vs Austin

**Group members:**
*Garret Bradley,*
*Martha Griggs,*
*Bruce Ly,*
*Soujanya Pentyala,*
*Claudia Yurrita,*

### Outline:

A “hot market"(hotness) is a real estate market with low inventory combined with lots of buyers looking for the perfect place.
For this project, our goal is to compare housing inventory (count), price point($) and day on market(count) among the two cities Dallas and Austin & determine which is more desirable based on these three factors. We will support our conclusion using visualization and metrics derived from the analysis.

### Question:

Based on the three factors which of the two cities is "hotter"?

### Factors used for comparison

**House availability**
**Pricing**
**Days of properties on the market**

### Datasets to be used:

Time period of data used for analysis :  February 2012 to December 2022

Redfin 2023, Redfin website, California USA, accesed 08 February 2023, <https://www.redfin.com/news/data-center/> 

[Link to REDFIN HOMEPAGE](https://www.redfin.com)

[Link to REDFIN DATACENTER](https://www.redfin.com/news/data-center/)



|TASK |RESPONSIBLE|
------|------|
| -[] Get the info                          | MG|
| -[] Make data frame and cleansing         | CY|
| -[] Find possible relations               | CY MG SP|
| -[] Create plot charts for visualization  | CY MG SP|
| -[] Statistical analysis                  | CY MG|
| -[] Written analysis and conclusions      | TBD|
| -[] API development and visualization     | BL|
| -[] General Review                        | GB|
| -[] Upload documents to Github            | MG|
| -[] Read.Me document                      |BL CY GB MG SP|
| -[] Powerpoint presentation               |BL CY GB MG SP| 

## Overview

The real estate market in US ..... in Texas !!!!!!!FILL THIS PLEASE
In the last years ....


## Definitions:

***Days on Market***:
The number of days between the date the home was listed for sale and when the home went off-market/pending sale covering all homes with an off-market date during a given time period where 50% of the off-market homes sat longer on the market and 50% went off the market faster. Excludes homes that stay on the market for more than 1 year. 

***Inventories***:Total number of active listings on the last day of a given time period.

***Median Average Price***:The final home sale price covering all homes with a sale date during a given time period where 50% of the sales were above this price and 50% were below this price.

## Outline of the project

We decided to run tests of three different variables (inventories, sale prices and days on the market) between  two cities (Austin and Dallas) to determine which of the cities was more desirable. 

### The hypothesis we tested were:

-Inventories in Dallas are bigger than Austin's
-Days on Market in Dallas are bigger than Austin's
-Prices in Dallas are lower than Austin's

All of the above shoul be indicators that one house market has more movility-and demand- than the other.

## Current Offer on Austin

As of February 13, 2023 Zillow had 350 listings just in Austin county. There are 5 counties included in the metropolitna area.  

          !!!!!! BRUCE MAP WITH THE REQUESTED HOUSES !!!!!!
        

## Current Offer on Dallas

As of February 13, 2023 just in Dallas county there were 4023 houses on sale. The metroplex includes 19 counties.

          !!!!!! BRUCE MAP WITH THE REQUESTED HOUSES !!!!!!


## PRICES

-Historically the prices in both cities show an ascendent trend
-Austin prices have gone from a median sale price of $190,000 in February 2012 up to  $458,000 as of December 2022. This means an increase of 41% in our timeframe.
-On the other hand Dallas has seen its prices up from $160,000 to $402,000, a 51% increase. 


         !!!!!MARTHAS GRAPH WITH BOTH PRICEs!!!!

![Relation between Prices in Austin and Dallas](XXXXXX)

## INVENTORIES

-The inventories in both cities differ greatly, however the gap has decreased greatly sin ce the pandemic.

-In the period analyzed inventories in Austin and Dallas went from 6,541 and 17,066 houses to 73,76 and 10,137, this is an increase for Austin of 6% and a decrease for Dallas of 41%, respectively
-

![Inventories over time](.\images\Bar_graph_Inventory.png)

![Relation between Inventories in Austin and Dallas](.\data\Summary_variables.csv)

## DAYS ON THE MARKET

- XXXXXXX     Soujanya's findings!!!!
-Days on market passed from 74 and 83 to 70 and 45 in Asutin and Dallas. This means decreases of 5% and 46% in both cities. 

          !!!! DAYS ON MARKET GRAPH SOUJANYA


# HYPOTHESIS TEST

## Question: Is Austin real estate market hotter than Dallas's?

First we calculated the metrics for the variables on both markets. 

|City|Inventory_Mean|Median Sale Price_Mean| Days on Market_Mean|
|---|----|---|---|
|Austin|     6567.335878|              311.877863|            32.106870|
|Dallas|    13396.068702|              273.702290|            35.679389| 

|City|Inventory_Var|  Median Sale Price_Var|  Days on Market_Var|
---|----|---|---|
Austin|   2.375871e+06|           8187.569583|          150.865414|
Dallas|   1.215040e+07|            5284.641456|          148.265649|


From looking at the data we can deduce the behavour of the inventories in Austin and Dallas are totally different. However we can not say the same for the others. Running Ttests we saw the prices and days on the market variables also differ  between cities. 

These resultas are presented below:

Calculations for Inventory t-test: t-statistic(-20.5068) , p-value ( 0.0000)
As the p-value is less than our critical value (0.05) the hypothesis is rejected

Calculations for Median Sale Price t-test: t-statistic( 3.7645) , p-value ( 0.0002)
As the p-value is less than our critical value (0.05) the hypothesis is rejected

Calculations for Days on Market t-test: t-statistic(-2.3642) , p-value ( 0.0188)
As the p-value is less than our critical value (0.05) the hypothesis is rejected

These findings imply both markets are different and we can choose between them.

Conclusion:






