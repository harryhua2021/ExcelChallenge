# Overview of Project

The purpose of this analysis project was to refactor the Module 2 code to collect stock information in the years 2017 and 2018, then determine which stocks are worth investing. The purpose of refactoring is not to replace but to improve the efficiency of the original code with better organization and visualization.

# Result

By comparing the stock’s performance of the year 2017 and 2018, I noticed that in the year 2017 the stocks portfolio had primarily enjoyed high volumes of gain except for “TERP.” In 2018, despite a significant correction that caused losses to all but two stocks, 7 out of the 12 stocks had increased in value compared to 2017.
https://github.com/harryhua2021/ExcelChallenge/blob/f25d7da715d1e1d55fd9556dc172ab4d0878e536/Module_2_assignment/Resources/2017.png
https://github.com/harryhua2021/ExcelChallenge/blob/f25d7da715d1e1d55fd9556dc172ab4d0878e536/Module_2_assignment/Resources/2018.png
     

It is also noticeable that the runtime to process the code after the refactoring decreased by almost 75% from 0.496 seconds to 0.125 seconds compared to the original code, proving the value of the refactoring effort.
https://github.com/harryhua2021/ExcelChallenge/blob/f25d7da715d1e1d55fd9556dc172ab4d0878e536/Module_2_assignment/Resources/runtime_2017.png
https://github.com/harryhua2021/ExcelChallenge/blob/f25d7da715d1e1d55fd9556dc172ab4d0878e536/Module_2_assignment/Resources/runtime_before_2017.png


     



# Summary

## Pros and Cons of Refactoring the Code
Refactoring can help make a script run more efficiently. The advantages of a less tedious script with more variables instead of hardcoded values are apparent in this challenge. Refactoring the code can also be helpful in aspects such as additional debugging and adding annotations to help users understand the workflow of the script in a readable language. Nonetheless, refactoring may not always be ideal for complex scripts with multiple dependencies. In which case, changes may cause unexpected errors if the workflow of the original script is not fully understood.

## The Benefits of Refactoring All Stocks Analysis
As I have discussed previously, the Refactoring of all stocks analysis has significantly improved the runtime of the original all stock analysis script. The refactored script use variables such as Range("A1").Value = "All Stocks (" + yearValue + ")" instead of the hardcoded Range("A1").Value = "All Stocks (2018)" which provided users a popup window to key in the desired year in the VBS. The refactored version also has simplified the for loops such as using tickerVolumes(i) = 0 verses ticker = tickers(i), totalVolume = 0, which has contributed to the faster runtime of the refactored script.
