# Supervised-Learning-Project

Final-Project-Tableau
Project/Goals
The goal is to analyze and make connections between housing prices, consumer spending and the average Candadian's earnings.

Process
Step 1: Connecting Data Sources to Tableau
For all files except one this process was a simple drag and drop. weekly_earnings.json however was a mess that needed cleaning. I removed all the unrelated information from the json file and was left with just the information I needed to analyze the weekly_earnings of canadians over the years.

Step 2: Answering questions with the data.
• Compare the house price trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
-Range of housing index trend data: 78.81-100.86 = 22.6

-Range of actual benchmark price index data: 104.4 -245.5 = 141.1

It’s interesting to note that the range of the actual benchmark prices is far greater than the range of the housing index trend data. Housing prices increased much faster than the trend predicted, 16 times faster in fact. This is easily visually noticeable on the graphs below by seeing how much steeper the benchmark price index line is vs the trend index data.

• Compare this trend with the trend of office prices. Which one is getting more expensive, faster?
-Range of benchmark housing price index from 2005-2007(2005) to 104.44-130.92(2007) = 51

-Range of office price index from 2005-2007: 113.21(2005) to 134.64(2007) = 21.43

Comparing the change in office price index to the change in housing price index, not many of the years with data collected overlap. So, from the years we do have to work with, 2005-2007. We can say that the office price is growing 42% faster over this time period.

• Create a heatmap of Canada with current house prices for each available district.
image

• Are the price differences between different districts increasing?
Prices between different districts are changing at different rates.

Barrie (fastest)
Guelph (2nd fastest)
Quint, Simcoe, Tilsonburg (tied) However by 2020 they all show a very strong upwards trend.
• Compare the trend of house prices with earnings.
image

2005-2015 Average Single Family Home Average Price Range: $291,938(2005)-$866,558(2015) = $574,620 Average Monthly Income: $2947.00(2005)-$3814.00(2015) = $867

-129% Increase in monthly income.

-297% increase in average single family home price.

The average single family home price has increased by 297% from 2005-2015 and the average monthly income has increased by 129% in the same time period. The home price is increasing 168% faster than the average Canadian monthly income.

• Did people spend more of their earnings in 2014 than they did in 2001?
image

2001 Consumer Spend Index: 66.16 2014 Consumer Spend Index: 97.88

Yes, people did spend more of their earnings in 2014 than they did in 2001, about 32% more than back in 2001.

As a whole it seems as the years go on, consumers spend more of their earnings.

Step 3: Interesting pattern, trend or outlier from the data.
As the years go on, consumer spending increase, housing prices increases and so does the average canadians monthly earnings. However the amount of money needed to purchase things is growing much quicker than the average earnings of a Canadian citizen.

Another interesting outlier is between 1982 and 1983, the consumer spending index has grown massively compared to any other 1 year interval.

Results
I chose option 1: Standard Final Project.

Data Sources I used. Weekly earnings from 1.1.2001 to 15.4.2015 (weekly_earnings - CSV) Housing constructions from 1955 to 2019 (real_estate_numbers - CSV) House prices from 1.1.2005 to 1.9.2020 (real_estate_prices - EXCEL) Housing_price_index from November 1979 to September 2020 Office_realestate_index from November 1979 to September 2020 Consumer index from November 1979 to September 2020

Business context: People are spending more money than ever, now is a good time to be a merchant. Houses are more valuable than ever and the trend suggests this will continue, buying real estate at this time is favorable investment.

Challenges
Trying to import the json file into tableau was tricky, however I was able to use Python and the json library to clean the data and get it ready for analysis.

Limited domain knowledge at the start of the project, learned more as I did research on real estate terminologies.

Future Goals
If I had more time I would try and do one of the other non standard final projects, some of those topics interest me and I believe that curiosty would help me take my analysis skills to a new level.
