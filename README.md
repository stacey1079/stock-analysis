# VBA Module 2 Challenge Stock Analysis
## Overview of Analysis
In this Module 2 Challenge I was tasked with refactoring the code to analyze the stock market dataset that Steve was using.  Steve wanted a code that could analyze thousands of stocks in a quick amount of time.  So, he wanted code in the script that would count how long it took the program to loop through the data and output the runtime of the program in a message box so that he could compare run times between scripts.  There is also some font formatting in the script to show the headings in bold, and color formatting to show which stocks had a gain in volume (green), and which stocks had a loss (red).  Unfortunately, only 2 stocks were in the green.  
<br />
In order to refactor the script, I added an additional variable for tickerIndex in order to be able to identify each stock ticker as a group.  I also added three arrays in order to output the tickerVolumes, the tickerStartingPrices, and the tickerEndingPrices for each stock set.  I set the tickerVolumes, and tickerIndex to 0 to begin.  After looping over all the rows in the script to gather the data needed, the last loop was to loop through the arrays and output the data.  After running each script separately, it does show that the refactored script runs faster than the original script.
## Results
### This is the result for the original stock performance script for 2018:
![VBA_Challenge_2018](https://user-images.githubusercontent.com/45715246/204869434-cec1c7da-4883-420a-afa8-aa2ea6b9a774.png)
### This is the results for the 2018 Refactored Stock Performance script:
![refactoredVBA_Challenge_2018](https://user-images.githubusercontent.com/45715246/204869785-8988cd31-1619-4625-85fc-7604456a3634.png)
So, as you see when the code was refactored, it did run faster which will help Steve in the future when analyzing larger amounts of stocks.
## Summary
One advantage of refactoring code is in order for it to run faster.  This is demonstrated clearly, through this module 2 Challenge.  Another advantage was that the code seemed to look cleaner as it was more condensed.  The first script has 3 separate If statements, and the refactored code only has 1 If statement.
<br />
The only disadvantage I experienced, was that it took me a lot of time and a tutor's help to figure out how to make the code run with only 1 If statement.  I didn't realize I had to set my tickerStartingPrice cell before I could execute the If statement to run through.
