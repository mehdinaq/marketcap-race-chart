# marketcap-race-chart

#### Overview
I created an animated bar chart (aka race chart) to visualize the top 5 richest companies over time. Public companies are listed on stock exchanges and the stock price determines their value or market capitalization. I web scraped market capitalziation data from 2001-2021 and used the matplotlib library to show the top 5 companies with the highest market capitalizaiton over time in an animated race chart.

#### Data Source
Web scrape the market capitalziation data from [market cap data](https://companiesmarketcap.com/usa/largest-companies-in-the-usa-by-market-cap/). The timeframe of the data available is 2001-2021.

#### Data Munging and Plotting
Market cap data was extracted by looping over individual companies, and the data was aggregated into a time series format and modified to be appropriate for plotting. 
Within the jupyter notebook, the play button in the race chart begins the animation to show the market cap from 2001-2021; options are available to speed up/slow down the animation speed, start over from the beginning, and drag the scroller to adjust the year being shown.\



[Detailed Analysis here](https://github.com/mehdinaq/marketcap-race-chart/blob/main/Race%20Chart.ipynb)
\

![race chart market cap](https://user-images.githubusercontent.com/8281173/131232420-d133f36d-0ee5-4e82-a490-8986cbce7c5a.png)
\



https://user-images.githubusercontent.com/8281173/131233004-f9666737-be51-4725-913d-77af5577be68.mp4

