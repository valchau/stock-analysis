# stock-analysis

## Overview

This project provides Steve, a good friend from college with information about how to quickly analysis selected stocks in terms of their daily trading volume, daily opening and closing prices and whether or not each chosen stock is worth investing in.

## Analysis 
At first Steve wanted me to show him how automating the stock analysis would work for one stock with the ticker "DQ". That worked and ran quickly.
So then, Steve asked for a program that used 12 stocks he was interested in along with data he had collected for his project using the year 2018 and then generalizing the program to run 2017 as well. 

Finally after that program ran and gave him the desired results I though about program efficiency and I know from learning about Big O notation that a program with two loops might not run as fast as a program with one loop. In addition, creating one variable to hold data in a loop and continually refreshing the value of that one variable might be less efficient than creating arrays to hold the 12 stock values relating to prices and volume traded. I realize that arrays do have a limitation and therefore to generalize this program for more than 12 stocks will take a different kind of data structure. Therefore I refactored the subroutine to be more efficient.

## Results
In Conclusion, I ran both the original stock analysis program and the new refactored program for both 2018 and 2017 to see if my refactored code ran faster. I noticed that yes, the refactoring did help. 
Here are the results for 2018 for the original program and then the refactored program: 
[original stock analysis 2018](resources/VBA_module2_ 2018.png)   and
[refactored stock analysis 2018](resources/VBA_Challenge.png)

