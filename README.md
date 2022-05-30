# Chennai_House_Price_Prediction_Final_Project


## Problem Statement

Real estate transactions are quite opaque sometimes and it may be difficult for a newbie to know the fair price of any given home. Thus, multiple real estate websites have the functionality to predict the prices of houses given different features regarding it. Such forecasting models will help buyers to identify a fair price for the home and also give insights to sellers as to how to build homes that fetch them more money. Chennai house sale price data is shared here and the participants are expected to build a sale price prediction model that will aid the customers to find a fair price for their homes and also help the sellers understand what factors are fetching more money for the houses?

## Minimum Requirements

It is not sufficient to just fit a model - the model must be analysed to find the important factors that contribute towards the price. Also, it will be better to give a forecast range (range of permissible values) rather than a single estimate as it will help the customers to negotiate.

## Objective

The model must be analysed to find the important factors that contribute towards the sales price
It will be better to give a forecast range(range of permissible values) rathar than a single estimate as it will help the customers to negotiate.

## Data Description
## Data Set: https://github.com/Nithilan98/Chennai_House_Price_Prediction_Final_Project/blob/b853da21549dbd60f8468252ffd20f1bb317e994/train-chennai-sale.csv
## Features

PRT_ID -- Property ID

INT_SQFT -- The interior sq.Ft of the property

DIST_MAINROAD -- The distance of the property to the main road

N_BEDROOM -- The number of Bed rooms

N_BATHROOM -- The number of bathroom

N_ROOM --Toal Number of Rooms

QS_ROOMS--The quality Score assigned for rooms based on buyer reviews

QS_BATHROOM -- The quality score assigned for bathroom on buyer reviews

QS_BEDROOM -- The quality score assigned for bedroom on buyer reviews

QS_OVERALL -- The Overall quality score assigned for the property

SALE_COND -- The Sale condition

 * Normal
 * Abnormal
 * Adjland
 * Family
 * Partial
 
BUILDTYPE -- The type of buliding
 * House
 * Commercial
 * Others
 * UTILITY_AVAIL

Allpub: All public utilites
 * NoSewr:Electricity,Gas, and Water
 * NoSewa:Electricty and gas only
 * ELO: Elecctricty only
 
STREET
 * Gravel
 * Paved
 * No Access
  
MZZONE
 * A: Agriculture
 * C: Commercial
 * I: Industrial
 * RH: Residential High Density
 * RL: Residential Low Density
 * RM: Residential Medium Density
 * REG_FEE -- Resgistration fees for the property

COMMIS -- The Commission paid to the agen

SALES_PRICE-- The total sale price of the property

## Project Overview
   The ***RandomForest*** and ***XgBoost*** has better accuarcy score for the house price data set.
   
   Predict the house price range using XGBoost ML model.
   
   ### Sellers understand what factors are fetching more money for the Houses
   
   ***AREA***
   
    - Area is the Most important Feature for profitability,
    - Area plays a crucial Role for deciding the best price of the houses.
    - The area with more facilites will have higer price.
    - The area with low facilites will have low price.
    - In Chennai, T.Nagar has highest house price.
    
  ***BUILDTYPE***
  
    - Buildtype is the second most important Feature for better investments.
    - Commercial Houses are most expensive compared to normal house.
    - Commercial buildings are hospitals, shopping malls,stores,IT companies etc.,
    - The investment of commercial building is more valuable than normal houses for the future profits.
    
 ***SQUARE FEET***
 
    - As the square Footage of the house increases, the price of the house also increases.
    - Square footage is essential for the viability of the investment.
    
 ***ZONE***
 
     - Zone also plays a major role in deciding the house price.
     - Commercial and Industrial zones are more profitable.
