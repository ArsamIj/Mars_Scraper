# Mars_Scraper

This challenge consists of examining scraping skills for webpages that can be inspected for their elements. 

## Deliverable #1
We scraped a web page consisting of news articles on Mars. Starting by creating a Beautiful Soup object and using it to extract text elements from the website, we extracted the titles and preview text of the news articles, and stored the scraping results in Python data structures.

## Deliverable #2
Using automated browsing, we visited the Mars Temperature Data Site, and inspected the page to identify the elements. We created a Beautiful Soup object and used it to scrape the data in the HTML table. We then assemble the scraped data into a Pandas DataFrame and outputed the data structure with the following headings.

id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location

We then analyzed the data and concluded the following:
1. There are 12 months on Mars
2. The curiousty rover rovided 1867 days worth of data
3. On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
4. Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
5. The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
