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
| -[] General Review                        | TBD|
| -[] Upload documents to Github            | MG|
| -[] Read.Me document                      |Everybody|
| -[] Powerpoint presentation               | TBD| 

## Overview

The real estate market in US ..... in Texas !!!!!!!FILL THIS PLEASE
In the last years ....


## Definitions:

***Days on Market***: The median number of days property listings spend on the market within the specified geography during the specified month. Time spent on the market is defined as the time between the initial listing of a property and either its closing date or the date it is taken off the market.

***Inventories***:

***Mean Average Price***:

## Outline of the project

We decided to run tests of three different variables (inventories, sale prices and days on the market) between  two cities (Austin and Dallas) to determine which of the cities was more desirable. 

### The hypothesis we tested were:

-Inventories in Dallas are bigger than Austin's
-Days on Market in Dallas are bigger than Austin's
-Prices in Dallas are lower than Austin's

All of the above shoul be indicators that one house market has more movility-and demand- than the other.

## Current Offer on Austin

As of February 2023  we had xxxx houses listed in the Austin market.

          !!!!!! BRUCE MAP WITH THE REQUESTED HOUSES !!!!!!

            !!!!!! SOME KIND OF INTRODUCTION !!!!!!

## Current Offer on Dallas

As of  February 2023  we had xxxx houses listed in the Austin market.

          !!!!!! BRUCE MAP WITH THE REQUESTED HOUSES !!!!!!

            !!!!!! SOME KIND OF INTRODUCTION !!!!!!




## PRICES

-Historically the prices in both cities show an ascendent trend
-Austin prices have gone from a median sale price of $190,000 in February 2012 up to  $458,000 as of December 2022. This means an increase of 41% in our timeframe.
-On the other hand Dallas has seen its prices up from $160,000 to $402,000, a 51% increase. 
-The correlation between Median Sale Price in Austin and Dallas is 0.981, which means they move alike.



         !!!!!MARTHAS GRAPH WITH BOTH PRICEs!!!!

    !!!SCATTER DALLAS AUSTIN (Scatter_plot_Median_Sale_Price.png)

## INVENTORIES

-The inventories in both cities differ greatly, however the trend followed is similar in both cities.
-Inventories in Austin and Dallas went from 6,541 and 17,066 houses to 73,76 and 10,137, this is an increase for Austin of 6% and a decrease for Dallas of 41%, respectively
-The correlation between Inventory in Austin and Dallas is 0.696, so both cities have a moderate relation.

      !!! INVENTORY GRAPH WITH BOTH CITIES (Bar_graph_Inventory.png)
     !!!SCATTER DALLAS AUSTIN (Scatter_plot_Inventory.png)

## DAYS ON THE MARKET
- XXXXXXX     Soujanya's findings!!!!
-The correlation between Days on Market in Austin and Dallas  is 0.658, showing a positive moderate relation between the two indicators.
-Days on market passed from 74 and 83 to 70 and 45 in Asutin and Dallas. This means decreases of 5% and 46% in both cities. 

          !!!! DAYS ON MARKET GRAPH SOUYANJA
        !!!SCATTER DALLAS AUSTIN (Scatter_plot_Days_on_Market.png)


# HYPOTESIS TEST

## Question: Is Austin real estate market hotter than Dallas's?

First we calculated the metrics / parameters  of the variables on both markets. 

|City|Inventory_Mean|Median Sale Price_Mean| Days on Market_Mean|
|---|----|---|---|
|Austin|     6567.335878|              311.877863|            32.106870|
|Dallas|    13396.068702|              273.702290|            35.679389| 

|City|Inventory_Var|  Median Sale Price_Var|  Days on Market_Var|
---|----|---|---|
Austin|   2.375871e+06|           8187.569583|          150.865414|
Dallas|   1.215040e+07|            5284.641456|          148.265649|


From looking at the data we can deduce the behavour of the inventories in Austin and Dallas are totally different. However we can not say the smae for the others. Running Ttests we saw the prices and days on the market variables also differ  between cities. Now we can prove if these variables are bigger/smaller in Asutin so they prove that market is more 'desirable' than Dallas.    








