# stock-analysis
Analysis of Green Energy Stocks
# Project Overview
The purpose of this project is to speed up the automated analysis of the stock workbook and allow for larger datasets to be analyzed quickly.  This analysis will show stock perfomances during the provided years: 2017 and 2018.

# Analysis Results
![Analysis of 2017 Results](https://github.com/marhanlang/stock-analysis/blob/main/Resources/VBA_results_2017.png) ![Analysis of 2018 Results](https://github.com/marhanlang/stock-analysis/blob/main/Resources/VBA_results_2018.png)

When comparing the stock performances in the provided years, 2017 proved to be an overall better year performance-wise than 2018. This might indicate lessened popularity of green energy stocks in recent years. When looking at individual stocks, however, the data shows that both ENPH and RUN have been able to maintain positive Return values.  If looking to invest successfully in green energy stocks, it would be prudent to pick a stock that can withstand the market fluctuations. DQ had the highest Return value drop from 2017 to 2018; it may be best switch investment considerations from DQ to ENPH or RUN.

## Speed Improvement Upon Refactoring
### 2017
##### ----------------------Before Refactor----------------------------------------------------After Refactor----------------------
![Speed Prior to Refactor 2017](https://github.com/marhanlang/stock-analysis/blob/main/Resources/VBA_2017_before.png) ![Speed Post Refactor 2017](https://github.com/marhanlang/stock-analysis/blob/main/VBA_Challenge_2017.png)

### 2018
##### ----------------------Before Refactor----------------------------------------------------After Refactor----------------------
![Speed Prior to Refactor 2018](https://github.com/marhanlang/stock-analysis/blob/main/Resources/VBA_2018_before.png) ![Speed Post Refactor 2018](https://github.com/marhanlang/stock-analysis/blob/main/VBA_Challenge_2018.png)

With the refactored code, the analysis is able to run around 0.3 to 0.4 seconds faster which can be beneficial when faced with large datasets.

# Summary
- Refactoring code can not only improve design and readablity but also increase the speed at which a code runs. The downside of refactoring is the possiblity of creating more bugs in the code. If a code is refactored poorly, it can have the opposite of it's intended effect.
  - EX: When refactoring the code for this project, it was easy to spend one minute creating a buggy code and spend one hour attempting to find an effective debugging solution. Such bugs included overflow errors from referencing incorrect variables or arrays.
  
- The project's original VBA code was simple, easy to read, and effective for the dataset presented but ran slower than the refactored code and may not work as efficiently on larger datasets.  A refactored code ensures that the analysis will run quickly and smoothly on larger sets of data.
