# Modular table scraper
A script to get the table data from any table in the HTML  of a website.

![image](https://user-images.githubusercontent.com/69304112/201654867-ec78def4-c2a7-4334-8e09-a86a9f4c020e.png)

It also has the capability to show you what tables are in the page and then select the one you want.

To do this, make the second criteria None. Else, put the number of the wanted table there.

It returns a faithful representation of the table that can then be refined.

By being modular and automated, it then allows for the scraping of countless related pages (such as pages in a series) and for this data to then be collated.

For example, I used this to scrape two-party preferred polling place data for the 2018 Victorian state election.

By adding little more than a for-loop and the names of all seats, this quickly produced a huge table of TPP data from each polling place in the state. 

This could be then analysed for trends - and visualised in a scatter plot, as above.
