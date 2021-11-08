# Challenge_starter_code

## Overview of Project

### Purpose
The main objetive of the project is to show how refactoring a code on VBA could save time running the application.    

### Results
After refactoring the code there is a clear reduction on time spending to run the macro, starting from 0.94 sec (2017) to just 0.11 sec (2017). Similar results were also notice with 2018 analysis, from 0.97 sec to 0.14 sec. The difference in performance can attributed to the additional arrays allocated on the code. Therefore, the macro didn't have to go all the list 11 times, as coded in the initial macro. Running through all the lines just once and allocating the results to different arrays resulted in more efficient and faster way to run the macro.     

### Summary
The advantages and pros are efficiency in allocating the variables and faster time in showing the final result. However, you have a more complex task in hand, specially when you are refactoring a code already done that needs to be improved.