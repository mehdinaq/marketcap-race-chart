# marketcap-race-chart

### [Animated plotting using Web-scraped data](https://github.com/mehdinaq/marketcap-race-chart/blob/main/Race%20Chart.ipynb)

### Overview
I created an animated bar chart (aka race chart) to visualize the top 5 richest companies over time. Public companies are listed on stock exchanges and the stock price determines their value or market capitalization. I web scraped market capitalziation data from 2001-2021 and used the matplotlib library to show the top 5 companies with the highest market capitalizaiton over time in an animated race chart.<br /><br />

### Data Source
Web scrape the market capitalziation data from [website](https://companiesmarketcap.com/usa/largest-companies-in-the-usa-by-market-cap/). The timeframe of the data available is 2001-2021.<br /><br />

### Data Munging and Plotting
Market cap data from 2001-2021 was extracted by looping over individual companies, and the data was aggregated into a time series format and modified to be appropriate for plotting.<br /><br />Within the jupyter notebook, there are two versions of the animated chart; one has playback controls such as the play button to begin the animation, and options to speed up/slow down the animation speed, start over from the beginning, and drag the scroller to adjust the year being shown. The second chart can be saved as an mp4 video, and was embedded below<br /><br />

[Detailed Analysis here](https://github.com/mehdinaq/marketcap-race-chart/blob/main/Race%20Chart.ipynb)<br /><br />




https://user-images.githubusercontent.com/8281173/131233212-22f65aeb-91ad-4527-b0a0-d940a77e1470.mp4



