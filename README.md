# An Analysis of the stock market using VBA


## Overview

*The purpose of this project was to refactor a previously developed code in VBA for an analysis of the stock market. Initially we used data from multiple stocks for the years 2017 & 2018 and created various subroutines in VBA in order to determine the behaviour of their face value. Afterwards the code was modified to enhance the running time and include all the data.

## Results 


### Stock Performance

*As seen on the images of the analysis results in the year 2017 most of the stocks had a positive increase in price. The year 2018 proved completely different; only two stocks had a positive increase in face value. The causality of the behaviour is not possible to explain with the data available. 

![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/VBA_ANALYSIS_2017.png)
![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/VBA_ANALYSIS_2018.png)

## Code Performance 

### Comparing running times between codes

The original coded yielded a performance of 0.79 seconds 

![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/ORIGINAL%20CODE.png)

The refactored codes yielded significantly shorter running times

![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/VBA_Challenge_2017.png)
![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/VBA_Challenge_2018.png)

*The code was refactored adding new arrays and adding a single loop that outsource the outcomes to a separate loop making less iterations.
![Alt Text](https://github.com/ramonmhung/Stock-Analysis-/blob/main/resources/VBA_CODE.png)

## Summary

### Advantages vs Disadvantages 
*Refactoring could provide the advantage of making a code more effective without altering its behaviour and making it easier to understand. The problem with refactoring a code its the amount of time it could take if there’s a deadline and creating a new code would be more effective.

### How this applies to the VBA script 
*By reducing the amount of loops in the original code the memory needed to process the data is smaller making the running times shorter. Technically we made our script more effective.
