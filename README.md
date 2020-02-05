# behavior-lab-codes
So I mainly created this code because I was originally supposed to measure the reward taking behavior on rats during two hour sessions of self-administration training
I was given raw data with output codes that indicated when the reward was received and inbetween the ouput codes were the increments of time between each output code was taken in milliseconds
By hand, I added all the numbers/ converting them into minute and entering in the number of rewards received in each minute interval
After attempting to do a couple of these in this fashion, I decided to write a code to help expedite the process as well as reduce the number of human errors made
After days of coding, I finally managed to create a python code that could show the time points in which the animal received reward
For fun, I renamed excel sheet names to correspond to the animal number/ day of testing and was able to add this to the code in order to prevent any confusions between each group of data
To do it backwards, showing the reward received throughout time, I had to add a couple additional lines of code-- the most notable being the list of 0's that are replaced at nth 0's corresponding to the time n, at which the reward was received
Couple of slight changes later-- I added in another layer in which it now saves automatically into an excel file with all the names of the animals on top and the data written in columns
It is currently still in progress in becoming better, but it is user-friendly enough to be used by others and therefore I thought to share this code
Hope this helps with your data analysis
