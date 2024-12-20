## Question 1

Take a look at the file labeled `data/data2.txt`. Why might we have missing values or values that state "NO SIGNAL" in this dataset? While we are currently ignoring these values, what might be the risk of filtering these values out?

We may have values that state no signal as maybe there was a fault/error when figuring out the heart rate at that time. The risk of filtering these out is that the data won't be as acurrate which could posisbly skew our data. Filtering out No signal alters our data size which further alters our findings. 

## Question 2

While the "averages.png" and "maximums.png" graphs visualize typical values in our time-series data of heart rates and subsequently describe similar trends, the "stdevs.png" graph visualizes the standard deviations, which results in a graph with less apparent trends. In the context of heart rate, what does the standard deviation describe?

The standard deviation is describing the spread of the heart rate data points in relation to the average heart rate samples.

## Question 3

Run your `main.py` module and look at the graph labeled "averages.png." Roughly speaking, where do you see the time series experience a significant difference in values along the x-axis? Point out all x-values where you notice a drastic difference in future values.

Around the values of :

from 0- 3 we see a decent decrease

from about 5 to 8 we see a decrease 

10 - 11 there is a drastic inrease 

from 10-20 overall we see a big increase will small decreases from 12-16 along the way. 

20 being the peak height of the data 

from 25-30 we see the biggest decrease 

35-36 we see a decent increase follwed by a decent decrease right back at 40. 


at 40 there is increase but with dips aloing the way going up and down. 





## Question 4

Do you also notice a corresponding difference in values in the "stdevs.png" graph? If so, do these differences align with the "averages.png" graph? 

I somewhat see a resemblence. Around the same X-axis values i do notice significant differences in future values when looking at the stdevs image and average.

They algin with each other, but the drastic differences in future values are more frequent in the Stdevs image. 
