# Mission-to-Mars

## Overview
The intial part of this project focused on webscraping from the NASA websites on Mars.  Developer tools from the chrome browser were used to inspect the HTML on the page and identify the parts that we will want to scrape.  Splinter and BeautifulSoup were used to write a python script to scrape the data we wanted to use.  Flask was used to create a web application and Mongo was the database that was used to store our data.  A script was created to make it so the page can update with only a click of the mouse.  

## Results
The web app was created and is working as appropriately, data is scraped and then displayed on the webpage as intended.  The web page was optimized to include information on hemispheres of Mars.  Titles, full resolution images, and other info are scraped from the webpage and brought to our own.  This was accomplished using Flaks, beautifulsoup, mongo, and HTML.  

### Webpage Displays
The following is the script that was used to to pull data from the websites.  
![image](https://user-images.githubusercontent.com/88444529/153058822-6c676d14-6bd7-4a83-a3a2-257f87503812.png)
The following image displays the webpage using Bootstrap, CSS, and HTML code as well as the button that can be used to scrape new data.
![image](https://user-images.githubusercontent.com/88444529/153059168-e374d794-3bc9-498a-9c48-f55ebf5b4822.png)
![image](https://user-images.githubusercontent.com/88444529/153059266-2d32bbcc-fb79-4bfc-802d-0c209c00f1e2.png)

# Conclusion
A web app and page were successfully created by scraping the NASA website for the appropriate hemisphere images and a button is also displayed to scrape new data as the webpage is updated.
