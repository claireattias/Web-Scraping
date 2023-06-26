This activity extracts information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. It scrapes data from two websites (https://static.bc-edx.com/data/web/mars_news/index.html and https://static.bc-edx.com/data/web/mars_facts/temperature.html) and stores the data in Python objects.

Part 1: Scrape Titles and Preview Text from Mars News
-

- Automated browsing (Splinter) was used to visit the Mars news site
  
- The page was inspected to identify which elements to scrape

- A Beautiful Soup object was created and used to extract text elements from the website

- The titles and preview text of the news articles were extracted


Part 2: Scrape and Analyze Mars Weather Data
-

- Automated browsing (splinter) was used to visit the Mars Temperature Data Site

- The page was inspected to identify which elements to scrape

- A Beautiful Soup object was created and used to scrape the data in the HTML table

- The scraped data was assembled into a Pandas DataFrame

- The dataset was analyzed using Pandas functions

