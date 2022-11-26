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
[original stock analysis 2018](resources/VBA_module2_2018.png)  and
[refactored stock analysis 2018](resources/VBA_Challenge_2018.png)

Here are the results for 2017 for the original program and then the refactored program: 
[original stock analysis 2017](resources/VBA_module2_2017.png)  and
[refactored stock analysis 2017](resources/VBA_Challenge_2017.png)

## Summary
In general, there are some benefits from refactoring code if your refactoring is done correctly and tested well:
* Simplified support and code updates. 
* Save time and money in the future. 
* Reduced complexity for easier understanding since later programmers might not understand tricky code 
* Maintainability and scalability

For code that has been in production for a while and was fully tested, refactoring it might
* not be tested as thoroughly as the original code was
* introduce new errors or complexity that weren't in the original code 
* use new data structures or features that are later deprecated in later versions of the programming enviroment
* be costly unless the existing code has become unstable, unusable or unsupported if it bridges to other code that changes versions

For our specific project here, the refactoring did help immensely with making the code run faster. However, 12 stocks is a very small set of data. In order to really know if refactoring to use arrays and reducing the complexitity of the double for loop to use single for loops, you might want to have a much larger set of stocks given to test out the program. In addition, the programs both run quickly because there is little user input. A more realistic example would have the user either input a file to read in the selected data or would have another macro reading in the file and this stock analysis macro to analyze it. Anyway, if you view the resulting images provided above you can see clearly that this small set of 12 stocks runs much more 
