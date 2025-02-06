# full-web-scraping-and-data-analysis-project

For this project I combined my skill of web scraping to analyze weather data from Mars, collected by NASA's Curiosity Rover. 

This poroject was broken up into 2 parts: 
-- Scrape titles and preview text from Mars news articles
-- Scrape and analyze Mars weather data, which exists in a table

Part 1: 

First, was to visit the Mars news site and inspect the page to identify which elements to scrape. Then using Beautiful Soup Object tp extract text elements from the website, such as titles, preview text of the articles. This was then stored in a python dictionar and stored as a Python list. 

Part 2: 

In this section I focused on scraping and analyzing the Mars weather data. Beatufil Soup object was created and used to scrape the data in the HTML table. The scarped data was then assembled into a Pandas DataFrame containing the same information found on the HTML data. Onced this was complete I was able to answer the following questions:

--How many months exist on Mars?

--How many Martian (and not Earth) days worth of data exist in the scraped dataset?

--What are the coldest and the warmest months on Mars (at the location of Curiosity)?

--Find the average minimum daily temperature for all of the months.

--Which months have the lowest and the highest atmospheric pressure on Mars? 

--About how many terrestrial (Earth) days exist in a Martian year? 

The final dataset is exported as a CSV file (mars_weather_data.csv), which contains the cleaned and analyzed weather data.
