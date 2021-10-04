# VBA of Wallstreet: an analysis of the trading history of green energy stocks in 2017 and 2018

## Overview of Project
Steve is a finance professional interested in analyzing green energy stocks for his parents. He likes the spreadsheet tools I have built for him thus far, yet seeks to expand the tool for a wider market. The current code is inefficient and would not process a larger data set in a timely manner. The current code must be refactored to become more efficient. 

## Analysis
The analysis was performed on data compiled from green energy stock trades from 12 companies for the years 2017 and 2018. We arrived at the Total Daily Volume by adding up the daily trade volumes for a stock in a given year. To arrive at the return for a stock we divided the closing price of the stock on the last day of the year by the price of the stock at closing on the first day of the year. We took this value and subtracted 1. We set up color coding to identify stocks with a positive return. Green indicates a positive return, while red indicates a negative return. We installed a pop up to measure the length of time required to run the analysis upon entry of the year in the input box pop up.

## Results
### Stock Values
In 2017, most of the stocks had a positive return. **(Fig. 1)**. Green energy looked to be an expanding market. In 2018 the trend reversed and nearly all of the stocks showed losses. **(Fig. 2)**. There may be opportunity to buy the stocks at a low if it is thought that the stocks may return to 2017 price levels.

![VBA_Challeng_2017](https://user-images.githubusercontent.com/88675415/135904949-2184a59a-07e5-40c3-b3e8-f3faff1e134b.PNG)


**Figure 1:** Green Energy Stock Analysis 2017. Green indicates a positive return. Red indicates a negative return. The pop up shows the time it took to perform the analysis.

![VBA_Challeng_2018](https://user-images.githubusercontent.com/88675415/135905247-cee7f2b7-3f1a-4e6e-91e8-fe6792fce9ef.PNG)

**Figure 2:**  Green Energy Stock Analysis 2018. Green indicates a positive return. Red indicates a negative return. The pop up shows the time it took to perform the analysis.

### Code Speed
The original code ran in .7 seconds for 2017 **(Fig. 3)** and .7 seconds for 2018 **(Fig. 4)**. Compared to the refactored code the original ran slower. The updated code ran in .07 and .08 seconds for the respective years. **(Figs. 1 & 2)**. The updated code would help if we were to use the tool for an expanded data set.

![2017 Original Code Speed](https://user-images.githubusercontent.com/88675415/135906859-9c78bff6-5adf-4640-b5bb-097891d3b472.PNG)

**Figure 3:** Analysis time 2017 stocks using original code.

![2018 Original Code Speed](https://user-images.githubusercontent.com/88675415/135906889-0154fe44-c7b7-4cda-9a6a-477ccb935695.PNG)


**Figure 4:** Analysis time 2018 stocks using original code.


## Summary
### Advantages and Disadvantages of Refactoring
Refactoring code can increase the legibility of code and can increase speed. However, refactoring code can take time. This time could be used on other projects of potentially greater significance.
### Advantages and Disadvantages of this Refactoring this Script
The original code worked and did not have bugs. I have rigorously tested my new script but there is potential for bugs to be discovered upon his application of the new macro. This new code runs significantly faster and is better for use on large data sets, a huge advantage. The disadvantage was that refactoring the code has an opportunity cost.

