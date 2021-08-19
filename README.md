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
![Original_Code(1)](https://user-images.githubusercontent.com/87148177/130001296-be297a97-2e78-4f81-84dc-8969ac0db442.png)
![Original_Code(2)](https://user-images.githubusercontent.com/87148177/130001341-2661604f-e549-4659-92c1-db280ac42238.png)
### And Refactored Code
![Refactored_Code(1)](https://user-images.githubusercontent.com/87148177/130001365-7eb00b39-b689-4ec0-868b-5bbf85773af9.png)
![Refactored_Code(2)](https://user-images.githubusercontent.com/87148177/130001374-18373f50-cfb5-4a0c-9f86-a6bcc21d419f.png)
### Script Times
When running the refactored code, it was significantly faster than the original code.
Here are my original script times:
![Original_Time_2017](https://user-images.githubusercontent.com/87148177/130001398-9249b48f-737e-45c9-8311-d9329127ac4d.png)
![Original_Time_2018](https://user-images.githubusercontent.com/87148177/130001425-68a5c268-df27-4dc1-8771-5d9e8e75d9d6.png)
And my refactored times:
![Refactored_Time_2017](https://user-images.githubusercontent.com/87148177/130001437-76e6d7d5-96da-44c3-809c-70c21bf83c6a.png)
![Refactored_Time_2018](https://user-images.githubusercontent.com/87148177/130001447-80e38e3c-7195-4609-83cd-ba83331b8d14.png)
## Summary
### Pros and Cons of Refactoring Code
Refactoring code can improve the design of the code, can make it easier to understand, can help with finding bugs, and can make programming faster.
However, if refactoring is done incorrectly, it can mess up the code and potentially introduce new bugs.
### Refactoring This Code
First, refactoring this code made it easier to read. It is more condensed and doesn't require a seperate sub for the formatting table. 
Also, refactoring the code made it run much faster. The original code ran 2017 in about 0.9 seconds, while the refactored code ran it in about 0.1.
The original code ran 2018 in 1.1 seconds, while the refactored code ran it in about 0.2 seconds.




