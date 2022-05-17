# Stocks-analysis

## Project Overview

Steve wants to expand the database to include the entire stock market across several years, but to accomplish that he will requiere a more efficient code. The purpose of this project is to refactor the orginal code to increase efficiency and readability, and help Steve create a code that can run larger amounts of data.

## Results 

To refactor the code, first the tickerIndex was set to zero to access the ticker arrays and the three output arrays. Then two For loops were created to set the tickerVolumes to zero, loop over all the rows, increase the tickerVolumes and include the if-then statements.

<img width="784" alt="Refactored Code" src="https://user-images.githubusercontent.com/104380112/168705220-7d7a0a00-2631-4a6b-af15-f58e6ba1281e.png">

As a result, the macro run time decrease significantly for both years. The original macro took almost one second to run the analysis, whereas the new macro took for year 2017 = 0.0937 seconds and for year 2018 = 0.0859 seconds, as shown on the screenshots below. 

<img width="259" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/104380112/168705260-a988e28a-ff21-42a1-b476-05ff42976cfd.png"> <img width="264" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/104380112/168705269-e346117c-480a-441d-ac94-68b418e166d0.png">

## Summary

### Advantages or Disadvantages of Refactoring 

#### Advantages

- Improves efficiency – with the macro taking fewer steps it will use less memory and run the code faster
- Improves readability – simplifying the code and setting variables improves the logic and makes it easier for future users to read. Better readability also makes the code easier to maintaining and the process of debugging smoother.
- Improves reusability – by not adding specific terms such as 2017 or 2018, the code can be reused to include several years of data. 

#### Disadvantages 

- Time consuming – it can be time consuming or tedious to look line by line to find what could be simplify or improve

### Pros and Cons of Refactoring the Original VBA script

#### Pros

- Steve will be able to expand his database and include further years without increasing the macro run times or the risk of experiencing bugs. Also, he could easily add more stock tickers if needed without changing the entire code. 

#### Cons 
- It was time consuming to change the code and fnd the mistakes along the way

