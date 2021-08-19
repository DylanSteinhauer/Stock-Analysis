# An Analysis of Green Energy Stocks
We analyzed various green energy stocks for Steve's parents, who were initially interested in DQ. 
## Recommendations
I recommend that Steve's parents stay clear from DQ stock. It performs well in 2017, but accrues significant losses in 2018 (-62.6%). I recommend investing in either ENPH or RUN. ENPH had big gains in 2017 (129.5% growth) and 2018 (81.9%). In addition, RUN had 5.5% growth in 2017 and 84% in 2018.
# VBA Challenge
## Purpose
The purpose of this challenge is to refactor the code for Steve's parents so that it can run effectively and efficiently. If refactored correctly, the code script should run faster.
## Results
In order to make the code more efficient, four different arrays were created: tickers, tickerVolumes, tickerStartingPrices, and tickerEndingPrices.
I matched the other three arrays with the tickers array by using the variable tickerIndex.
I used this variable to assign the tickerVolumes, tickerStartingPrices, and tickerEndingPrices to each ticker symbol before running through the dataset
This helps the script run more efficiently.
### Here are screenshots of my original code:
![Original_Code(1)](path/to/Original_Code(1).png)
![Original_Code(2)](path/to/Original_Code(2).png)
### And Refactored Code
![Refactored_Code(1)](path/to/Refactored_Code(1).png)
![Refactored_Code(2)](path/to/Refactored_Code(2).png)
### Script Times
When running the refactored code, it was significantly faster than the original code.
This is evidenced by my screenshots:
![Original_Time_2017](path/to/Original_Time_2017.png)
![Original_Time_2018](path/to/Original_Time_2018.png)
![Refactored_Time_2017](path/to/Refactored_Time_2017.png)
![Refactored_Time_2018](path/to/Refactored_Time_2018.png)
## Summary
### Pros and Cons of Refactoring Code
Refactoring code can improve the design of the code, can make it easier to understand, can help with finding bugs, and can make programming faster.
However, if refactoring is done incorrectly, it can mess up the code and potentially introduce new bugs.
### Refactoring This Code
First, refactoring this code made it easier to read. It is more condensed and doesn't require a seperate sub for the formatting table. 
Also, refactoring the code made it run much faster. The original code ran 2017 in about 0.9 seconds, while the refactored code ran it in about 0.1.
The original code ran 2018 in 1.1 seconds, while the refactored code ran it in about 0.2 seconds.




