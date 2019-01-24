# FB_birthdays_R_analysis
## Description

This project is part of the Udacity Data Analyst Nanodegree under the learning
of EDA (exploring Data Analysis) for one variable

##  Data 
data here is about my friends birthdays.

## How to download your own data?
you can download your own data as per steps [here]('https://www.facebook.com/help/152652248136178?helpref=uf_permalink')

# Tasks Required:
Your task is to investigate the distribution of your friends'
birth months and days.


 Here some questions you could answer, and we hope you think of others:
 
* How many people have the same birthday as you?
* (Reserve time with them or save money to buy them a gift!)
* Which month contains the most number of birthdays?
* How many birthdays are in each month?
* Which day of the year has the most number of birthdays?
* Do you have at least 365 friends that have birthdays on everyday of the year?

## Skills gained:
* You will need to do some **data munging** and additional research to
 complete this task. This task won't be easy, and you may encounter some
 unexpected challenges along the way. We hope you learn a lot from it though.
* You can expect to spend 30 min or more on this task depending if you
  use the provided data or obtain your personal data. We also encourage you
 to use the lubridate package for working with dates. Read over the documentation
 in **RStudio** and search for examples online if you need help.
* You'll need to export your Facebooks friends' birthdays to a csv file.
* You may need to create a calendar of your Facebook friends’ birthdays
  in a program like Outlook or Gmail and then export the calendar as a csv file.
**_Here I open the data in Google drive and download it as CSV_**
* Once you load the data into R Studio, you can use the strptime() function
  to extract the birth months and birth days. We recommend looking up the
  documentation for the function and finding examples online.
* We've included some links in the Instructor Notes to help get you started.


Once you've completed your investigation, create a post in the discussions
 that includes:
   1. any questions you answered, your observations, and summary statistics
   2. snippets of code that created the plots
   3. links to the images of your plots
You can save images by using the ggsave() command. ggsave() will save the last plot created.
For example...
```
qplot(x = price, data = diamonds)
ggsave('priceHistogram.png')
```
ggsave currently recognises the extensions eps/ps, tex (pictex),
pdf, jpeg, tiff, png, bmp, svg and wmf (windows only).

## Languages:
R
## Contribution:
Feel free to add if you find something valuable to learn 
