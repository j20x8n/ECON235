java c
ECON235
Report Assignment PART 1   (40 marks)
Due   date: 5 pm,   August 30, 2024. Upload your answers and R script. in the   Assessment 2 section on Moodle.
Instructions:      This is an individual assignment. Use the starter R script. form      Moodle to create the dataset of hotel prices for your assigned city (London,   Paris or Rome). The answer the questions below and submit your answers along with the full R script. Include your name, student number and tutorial   group.Style: We will not follow any particular style. for this part. Just type your   answers, include required tables and graphs, save it as a PDF file and      upload to Moodle along with your R script.
1.1 (2 marks) Make sure that'hotelbookingdata.csv'file is in your Working   Directory and then run the starter R   script. to create a dataset for your            assigned city. How many observations does it have?
1.2 (10 marks) Let’s have a   look   at the following variables:
Variable
Typical value
Type
accommodationtype
_ACCOM_TYPE@Hotel
character string
guestreviewsrating
3.7   /5
character string
distance1
9.0   miles
character string
distance2
7.5   miles
character string
All of them are character strings which contain superfluous characters that   we don’t need. Clean these variables so that they look as follows (pay attention to the variable type). Which commands will you use to do this?
Variable
Typical value
Type
acc_type
Hotel, etc
character string
rating
3.7
double
distance1
9.0
double
distance2
7.5
double
1.3 (4 marks) Tabulate these four variables to check if there are   any missing (NA) values. Restrict the dataset only to observations with non-   missing values. How many observations did you have to drop (if any)?
1.4    (2 marks) Now restrict your dataset only to observations with account   type “Hotel” and star rating of 3 or 4 stars (use the star 代 写ECON235 Report Assignment PART 1Java
代做程序编程语言  variable). How many observations you ended up with?
1.5 (2 marks)    Produce a summary table showing the standard summary statistics for all variables in your dataset (include the table in your answer)
1.6 (3 marks) Now produce a more detailed table for the two key variables   price and distance1. It should include the following statistics: Mean,   Median, SD, Min, Max,P25, P75.   (include   the   table   in   your   answer). How   do these statistics in your city compare with those in Vienna?
1.7 (4 marks) Produce the histograms showing the distribution of the two   variables price and distance1 in your sample. Do you see any extreme values in these two variables in your city? Argue if you want to keep or discard these extreme values (if there are any) and modify your dataset   accordingly. (include the graphs in your answer)
1.8 (3 marks) Reproduce the histogram for the two variables with your new   dataset, but now add the kernel density graph to the histogram.
Challenge   question (optional): Can you produce a graph of kernel density plots comparing the distribution of hotel prices in your city and Vienna (see   Lecture 3 for the London-Vienna comparison). We have not done this in tutorials, so you will need to figure out how to do it.
1.9 (10 marks) Now let’s make some basic conditional   mean comparisons.   Split your sample into two parts based on the median distance from the city centre (median of distance1 in your dataset):
Near = all the hotels with the distance from the city below   or   equal to the   median distance
Far = all the hotels with the distance from the city larger than the median   distance
Now compute the mean hotel price in the Near and Far subsamples. What   did you find? Does your finding make sense to you? How would you make this comparison more meaningful (you don’t need to implement it,   just discuss what you need to do).







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
