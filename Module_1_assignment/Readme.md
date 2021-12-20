Written Analysis for the Kickstarter Challenge Project 

# Purpose of the project

The purpose of this project is to provide a numerical and graphic understanding in regards to Louise’s fund-raising campaigns for her play “Fever”. Through the combination of various data points, I was able to create numerical tables and graphic visualizations that show both the current progress and predict future trends of her campaigns. 

# Analysis and Challenges

## Project deliverable one Analysis

As I attempted to solve the challenges in deliverable 1, first I launched a pivot table filtered by column “Parent Category” and “Years”. In this table, the successful, failed and canceled launches are organized by columns and displayed based on the month they occurred. From the table created, I then created a pivot chart named “Theater outcomes based on launch date”. The chart illustrated the data from the pivot table in a line graph manner, which made my understanding of her campaign trends much easier and direct.

One of the major challenges I encountered in this portion of the project is the different interfaces between Mac version of Excel and the Windows version. Despite the effort, in the Mac version, I was not able to convert the date in my pivot table from decimal numbers to readable form even the corresponding columns in the original sheet were filtered by “date”. This challenge delayed the progress of my project and I eventually was forced to switch to use Excel on my PC. I think this issue could be further looked into to help future students save time. The other challenge I encountered was understanding how layers work in the date filter section as the pivot table was filtered by year initially. Thru the help of my TA, I now understand that I am able to remove layers from filter until I reach the desired result.

## Project deliverable two Analysis
    
    In the deliverable 2 part of the exercise, I created a new table called “outcomes-based on goal”. By using countifs() to filter the columns from the original kickstart_challenge sheet, I was able to populate the success, fail, and canceled columns based on the respective ranges provided in the Goal column. After combining the number successfully, number failed and number canceled columns using SUM() function, the number of total projects column was then divided by the numbers in success, fail, and canceled columns to get the percentages that are required to fill the percentage columns of the table. The biggest challenge of this part of the exercise was to correctly populate the Number of successful, failed, and canceled columns. Because of the amount of input that is required in each countifs() function, each comma and quote has to be placed in the right place in order to make the functions work. It is also easy to miss to use both equal (=) and greater (>) or less than(<) to define the ranges in the goal column as for example, range 1000 to 4999 is >=1000 and <=4999.
    
# Results

## The two conclusions I draw from the Theater Outcomes by Launch Date.

The two conclusions I can draw from the Theater Outcomes by Launch Date are: (1) The fundraiser experienced the most success during the middle of the year. (2) The number of successful campaigns has declined when compared to the beginning of the year while the number of failures stayed about the same throughout the year. 

## Conclusion from the Outcomes-based on Goals

From the Outcomes Based on Goals Chart, I see a trend of decline in the success rate of plays as the goal amount increases. It is also worth mentioning that none of the plays were canceled based on the new data table. 

## Limitations of the dataset

The dataset did not account for the exchange rate amongst different currencies. The dataset also did not point out revenues are still being generated in failed or canceled plays.
 
## Possible tables and graphs we could create. 
“Pledged amount by currency/country.”
“Play by genre"