# web-scraping
 web-scraping

# Deliverable 1: Mars News Scraping

This Python script demonstrated how to scrape the latest news titles and preview texts from the Mars news website using Splinter and BeautifulSoup libraries.

## Step 1: Visit the Website

To begin the scraping process, the script first visited the Mars news website using Splinter:

### Visited the Mars news site
Automated browsing was used to visit the [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html).

## Step 2: Scraped the Website
Once the website was visited, the script created a Beautiful Soup object to parse the HTML content and extract all the text elements containing news titles and preview texts.

## Step 3: Stored the Results
After extracting the text elements, the script stored the titles and preview texts of the news articles in Python dictionaries and appended them to a list.

# Deliverable 2: Scrape and Analyze Mars Weather Data

## Step 1: Visit the Website

Automated browsing was used to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).

## Step 2: Scraped the Table

A Beautiful Soup object was created and used to scrape the data in the HTML table.

## Step 3: Stored the Data

The scraped data was assembled into a Pandas DataFrame.

## Step 4: Prepared Data for Analysis

The data types that were currently associated with each column were examined.

## Step 5: Analyzed the Data

The dataset was analyzed using Pandas functions to answer the following questions:

1. How many months existed on Mars?
2. How many Martian (and not Earth) days worth of data existed in the scraped dataset?
3. What were the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * The average minimum daily temperature for all of the months was found.
    * The results were plotted as a bar chart.
4. Which months had the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * The average daily atmospheric pressure of all the months was found.
    * The results were plotted as a bar chart.
5. About how many terrestrial (Earth) days existed in a Martian year? To answer this question:
    * It was considered how many days elapsed on Earth in the time that Mars circled the Sun once.
    * The result was visually estimated by plotting the daily minimum temperature.