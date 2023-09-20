# web-scraping Module 11 Challenge

# Background
This assignment calls for web-scraping and data analysis of a specific website. There are many elements to HTML, such as identifying the *id* and *class* attributes. 
You will use the knowledge on HTML in order to extract information via both automated browsing with Splinter and HTML parsing with *Beautiful Soup*.
This overall requires you to collect the data, organize and store the data, analyse the data, and then be able to visually communicate the findings.

There are two parts:
- Deliverable 1: Scrape titles and preview text from Mars news articles
- Deliverable 2: Scrape and analyze Mars weather data. This can be found in the table

# Part 1: Scrape Titles and Preview Text from Mars News
- Start by Visiting the MArs news site and inspect teh page to identify wchich elements will need to be scarped. *try using the Chrome DevTools*
- Create a *BeautifulSoup object* to use to extract text elements from the website
- Extract the titles and preview text of the news articles that you scraped.

# Part 2: Scrape and Analyze Mars Weather Data
- Use <automated browsing> to visit the Mars Temperature Data Site. Inspect the [age to identify the elements to scrape. url: *https://static.bcedx.com/data/web/mars_facts/temperature.html*
- Create a *BeautifulSoup object* and use it to scrape the data in the HTML table
- Assemble the scraped data into a Pandas DataFrame. *The columns should have the same headings as the table on the website.*
- Examine the data types that are currently associated wuth each column. *This is important to do before analyze your dataset so we can use panada functions to manipulate the data*
- Analyze your dataset by using Pandas functions to answer the questions provided.
