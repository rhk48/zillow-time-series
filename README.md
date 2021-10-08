# Zillow Time Series Modeling: Texas 
Authors: 
- Lorela Blaka
- Seth Kaufman
- Rashid Karriti

# Overview
![https---specials-images forbesimg com-dam-imageserve-1091770016-960x0 jpg?fit=scale](https://user-images.githubusercontent.com/82670256/136472341-8f62454c-20bc-4df1-abc1-e6ab32aa90e9.jpeg)

This project analyzes a series of time series models to provide a real estate investment firm to break into the Texas housing market. Based on a series of filtering, we found that the top 5 zip codes are:  
- 76108: Fort Worth (Dallas area)
- 75052: Grand Prairie (Dallas area)
- 75104: Cedar Hill (Dallas area)
- 77571: La Porte (Houston area)
- 79423: Lubbock (Northern area)

![tejas](https://user-images.githubusercontent.com/82670256/136484300-b6cab662-0eef-4af2-8a60-f2b49a37fd69.PNG)

# Business Understanding
As independent real estate consultants, we have been contracted by Texas Real Estate Investments (TREI) to find the top 5 zip codes they should invest in that would offer them the greatest investment success. Based on our client's requests, we found that looking at the Affordability Score (the score representing the ability of a home buyer to pay their mortgage), and Average Return on Investment(ROI) in a given zip code are strong indicators of whether a home in a given zip code is worth investing in for TREI. Our task is to identify what these top 5 zip codes are based on our predictions through several Time Series models and present our findings to the client. 

# Data Understanding and Preparation
The project utilizes Time Series Models, specifically focused on ARIMA and SARIMAX models, running several iterations on the models to see within what range our models can capture the best prices of the zip codes. The data provided to us was from the Zillow Housing Data spanning from 1996 to 2018 with about 14,000 Zip codes within the United States, which after filtering down to specifically Texas we are left with 1,930 zip codes to filter through. Our other dataset comes from Missouri Census Data Center, Median Family Income that provided us insight to calculating our Affordability Score.

# Results
After narrowing down our top 5 zip codes, we began to look at what the Average ROI of the given zipcode looks like. We found that all of the ROI's of each of our zip codes was significatly larger then the average ROI across all zip codes in the Texas. This further suggests that these zipcodes are some of the best zipcodes across the state.   
![Unknown](https://user-images.githubusercontent.com/82670256/136482733-73546361-3a38-4675-a6fe-1b6012122bbd.png)
 
Further more, when looking at the a time series of what the average afforabitly score was across all zipcodes across the state and specifically looking at the average affordabitly score in each given zip code, we find that our top five zip codes have some of the best scores across the state. This ensures that TREI can trust that in these 5 zip codes, their is greater chance that home buyers will be able to pay off their home. 
![Unknown-2](https://user-images.githubusercontent.com/82670256/136482764-9d5a619f-b2af-4f79-b2fc-f56ea49e6259.png)

After a series of optimization of our ARIMA models for each of the zip codes and manually testing the hyper parameters for each zipcode, we found that we can predict that an increase in price will occuur overtime. 
![Unknown-3](https://user-images.githubusercontent.com/82670256/136556683-f90816d1-0df4-45be-bd78-6b734e8f1935.png)

# Conclusion 
TREI should invest in homes in the top 5 zipcodes in the given areas we prove to be the best place for long term investment success, based on our Afforadiblity Score and ROI. 

# Future Steps
For a more comprehensive evaluation for TREI to find future to find more zip codes that have investment successes we should inquire into:
- Expanding the model to work for other states
- Get the model to forecast more than a few years

# Project Structure
  ```
├── README.md
├── data      <-- CSV 
├── Individuals Notebooks       <--- Directory for individual workspaces
│   ├── seth
│   ├── lorela
│   ├── rashid
│   
├── TimeSeriesPresentation.pdf   <-- non-technical presentation slides
├── final_notebook.ipynb    <-- Jupyter Notebook containing codes detailing project's analysis 
└── .gitignore
```
