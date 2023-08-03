# Web-scraping Challenge
- In this challenge, we extend to scraping various types of data, including HTML tables and recurring elements like multiple news articles on a webpage.

## Part 1: scrape Mars news articles for their titles and preview text

- To scrape Mars news articles, we'll use automated browsing with Splinter to visit the Mars news site. After inspecting the page, we'll identify the elements to scrape. To extract text elements, we'll create a Beautiful Soup object and use it to navigate the website's HTML.
- We'll specifically extract the titles and preview text of the news articles. Each title-and-preview pair will be stored in a Python dictionary. All the dictionaries will be collected into a Python list.
- Once the scraping is complete, the list of dictionaries will be printed in the notebook. And the scraped data will be saved to a JSON file for easier sharing with others.


## Part2: Scrape and Analyze Mars Weather Data

- To gather Mars temperature data, we will use automated browsing with Splinter to visit the Mars Temperature Data Site (https://static.bc-edx.com/data/web/mars_facts/temperature.html). By inspecting the page, we will identify the elements to scrape and create a Beautiful Soup object to extract the data from the HTML table.
- Once the data is extracted, we will assemble it into a Pandas DataFrame with the columns corresponding to the table on the website.
- Next, we will analyze the dataset using various Pandas functions to answer the following questions:
    1. How many months exist on Mars?
    2. How many Martian days worth of data are in the scraped dataset?
    3. What are the coldest and warmest months on Mars at Curiosity's location? To find this, we will calculate the average minimum daily temperature for each month and plot the results as a bar chart.
    4. Which months have the lowest and highest atmospheric pressure on Mars? To answer this, we will find the average daily atmospheric pressure for each month and plot the results as a bar chart.
    5. About how many terrestrial (Earth) days exist in a Martian year? To estimate this, we will consider the time it takes Mars to circle the Sun and plot the daily minimum temperature.
- Finally, we will export the DataFrame to a CSV file for further use or sharing.
