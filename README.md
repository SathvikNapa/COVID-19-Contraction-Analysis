CORONA Pandemic - Analysis
--------------------------

This project deals with the statistical analysis of the contraction of the widespread Corona Virus as pf dated April 04, 2020

Data observed in this project is a time-series data of all the countries, Provinces affected by Corona Pandemic.

THE ANALYSIS Focuses on the following:
-------------------------------------

  **World Wide Data Analysis**
  
  **Country Wide Data Analysis**
  
  **Province-wise Data Analysis**
  
  **Death Rate Calculation**
  
  **Weighted Death Rate Calculation**
  
  **New Cases/Day for each province and country**
  
  **Forecasting the effects of COVID-19 Pandemic Worldwide as well as Country-Wide**

Functions Included in the Analysis:
----------------------------------

***Analysis by Country***
**analysis_by_country(w3_df,country)**

*Pass the arguments dataframe and country name to get the time series analysis by country*

***Province-wise Death Ratio and Confirmed vs Fatalities***
**province_wise_deathratio(w3_df,country)**

*Pass the arguments dataframe and country name to get the Province-wise Death ratio and Confirmed Cases against Fatalities metrics*

***Rise in Cases as well as Fatality per day by Province***
**Rise_in_Cases(w3_df,country,province)**

*Pass the arguments dataframe, country name and province name to get the Province-wise increse in Confirmed Cases each day and Province-wise increse in Fatalities each day*

***Rise in Cases as well as Fatality per day by country***
**Rise_in_Cases_country(w3_df,country)**

*Pass the arguments dataframe and country name to get the country-wide increse in Confirmed Cases each day and country-wide increse in Fatalities each day*
