# ADS506
Final project for ADS506 - Times Series Analysis

## Title of Your Time Series Final Project:
Litecoin Cryptocurrency Forecast – Variations on the Autoregressive Moving Average Model:  a Time Series Analysis


### Problem Statement: 
Short Description of Your Time Series Project and Objective(s): 
After being founded in 2011 by Charlie Lee as a peer-to-peer digital currency, Litecoin Foundation has experienced a fair share of peaks and troughs in the cryptocurrency space for reasons not affected by price alone. For example, many people still remain skeptical as to the real value behind the blockchain phenomenon that was largely exacerbated by the explosion of bitcoin (BTC). Litecoin came soon after, trading substantially low at roughly $3.00 per coin. At the moment of this report, it is trading at $247.86, and is number 14 on the list of all cryptocurrencies of coinmarketcap. We will endeavor to analyze the behaviors and patterns of litecoin for the past 10 years and use (i.e. seasonal) models to forecast a sound and proper price trajectory that will give prospective (especially conservative) investors a healthy outlook for future growth.

#### Name of Your Selected Dataset: 
Litecoin (LTC) data from tidyquant() package

### Description of Your Selected Dataset (data source, number of variables, size of dataset, etc.): 
Data source: tidyquant() package - 
LTC <- tq_get("LTC", from = "2015-1-1", to = "2021-11-30") %>%
Shape: 1,731 rows 

