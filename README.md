# stock-analysis
Performing analysis on stocks to uncover trends

## Overview of Project
Steve has asked to help him analyze a handful of green energy stocks in effort to help his parents diversify their portfolio. He has given an excel file containing all the stock data he'd like to analyze for them. By using VBA to automate this task.

### Purpose of the project
The purpose of this task is to create a code that will automate stock analyses and to create a refactored version of this code.


## Results


### 2018 Stock Analysis

If you held any of stocks that are highlighted green, you would have made some money in 2017. While having shares in those stocks are good for 2017, there is a big difference in returns for 2018, which can be seen below. The only 2 stocks to have positive returns in 2018 were ENPH and RUN, which are highlighted in green. Those are the only two stocks that would have been profitable to hold during both 2017 and 2018.

![test](Resources/VBA_Challenge_2018.png)

### 2017 Stock Analysis
The code created 3 columns of output data which represent a stock's ticker, a stock's total daily volume, and a stock's return. The ticker is a unique identifier for each stock, the total daily volume is the daily amount of shares trades within a given stock, and the return represents how well a stock performs. In the code created, positive returns are formatted to the color green and negative returns are formatted to the color red. In the chart below we can see that, aside from TERP, all of the stocks exhibited positive returns during 2017. Terp had a -7.2% return and is highlighted in red.

![test](Resources/VBA_Challenge_2017.png)


### Differences between the Code and the Refactored Code 

Prior to refactoring the code, these scripts ran relatively slower. While the difference of a 1.2 seconds may not be too much for the run time, there are other advantages that we may encounter in the long run. While the output only shows the time difference, the code itself has an improved design and structure. The improved design helps a lot when trying to make adjustments to the code because it will be easier to read. The structure has improved and will prove to be very useful when debugging the code
![test](Resources/VBA_Challenge_2017_Original_Script_time.png)

### Comparing Refactored Code with the Original Script

Here were can compare the refactored code vs the original code. The refactored code has been redesigned to utilize arrays ("tickerStartingPrice", "tickerEndingPrice" and "tickerVolumes") as relative references store values that will be later used as output. The refactored code also gave me the opportunity to clean up the design for future users. Refactoring this code also gave me the opportunity to write more comments on each step of the code.
![test](Resources/Code_Comparison.png)

## Summary

To reiterate and the advantages of refactoring code is to see a faster run time, and to have a better code design & structure.Refactored code is quicker to run. Some of these difficulties came when rewriting loops utilizing variables as indexes and calling on arrays using variables as indexes. 

### The pros and cons of refactoring this code
The logic of the original script was easier to grasp but the code was more "step by step" because of the absolute referencing. It took twice the amount of time to refactor the original script but I believe that this refactored code will prove to be most useful when we have a dataset with all of many stocks across different markets.
