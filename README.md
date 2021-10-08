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
  
# Business Understanding
As independent real estate consultants, we have been contracted by Texas Real Estate Investment (TREI) to find the top 5 zip codes they should invest in that would offer them the greatest investment success. Based on our client's requests, we found that looking at the Affordability Score (the score representing the ability of a home buyer to pay their mortgage), and Average Return on Investment(ROI) in a given zip code are strong indicators of whether a home in a given zip code is worth investing in for TREI. Our task is to identify what these top 5 zip codes are based on our predictions through several Time Series models and present our findings to the client. 
# Data Understanding and Preparation
The project utilizes Time Series Models, specifically focused on ARIMA and SARIMAX models, running several iterations on the models to see within what range our models can capture the best prices of the zip codes. The data provided to us was from the Zillow Housing Data spanning from 1996 to 2018 with about 14,000 Zip codes within the United States, which after filtering down to specifically Texas we are left with 1,930 zip codes to filter through. Our other dataset comes from Missouri Census Data Center, Median Family Income that provided us insight to calculating our Affordability Score.
# Results
![Unknown](https://user-images.githubusercontent.com/82670256/136482733-73546361-3a38-4675-a6fe-1b6012122bbd.png)
- 
![Unknown-1](https://user-images.githubusercontent.com/82670256/136482761-12b3db9f-c1f5-4daa-a4ab-28522067de6e.png)

![Unknown-2](https://user-images.githubusercontent.com/82670256/136482764-9d5a619f-b2af-4f79-b2fc-f56ea49e6259.png)

# Conclusion and Future Steps 


# For More Information 

Lorela Blaka: lblaka@gmail.com <br />
Rashid Karriti: rhk48@georgetown.edu <br />
Seth Kaufman: sethkaufman7@gmail.com <br />

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
