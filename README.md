# Football Data Scraping with Selenium Project
Automate Sports Analytics 
## Overview
If you like sports, after every match you probably visit websites that offer free stats like final scores and player performance. Wouldn’t be cool to get that data after every new match? Or even better, imagine being able to use that data to create a report to find interesting insights about your favorite team or league.
That is the goal, to scrape a website that contains stats of your favorite sport. Most of the time this type of data is inside a table, so export the data in CSV format to read it with the Pandas library and find insights later.

Most sites with sports data use JavaScript to update the data dynamically. This means that we won’t be able to use the Beautiful Soup library for this project. Instead, we’ll use Selenium to click on buttons, select elements inside dropdowns, and extract the data we want.

## Contents:

- importing selenium libraries
- define the website, web driver path, and open the webpage
- find the needed elements and get the data from it
- store the collected data in a data frame
- write the stored data to a CSV file
- repeat same process by selecting a different country


## Reference
https://www.youtube.com/watch?v=UOsRrxMKJYk
