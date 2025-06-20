# AOC-Day-1

Problem Statement:
There is a sliegh keys that is missing and from the submarine need to figure out the trend of the depth measurements. This depth measurement is got by looking at the sonar sweep report. 

As an example, for the below measurements, need to count how many times the depth increases from the the measurement of the next.


199
200
208
210
200
207
240
269
260
263

Approach


Define a slice of integer data type 
initialize the slice with a depth of elements to be compared
Intitize count variable to 0 
loop through the slice to compare the current element with the next element 
if it is greater , increament count variable by 1

