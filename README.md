# Web-Scraping---SplinterHTMLBeautifulSoup

This project revolved full web-scarping and data analysis. Specifically identifying HTML elements on a page, identifying their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.

- Part 1 Deliverable: Scrape titles and preview text from Mars news articles.

- Part 2 Deliverable: Scrape and analyze Mars weather data, which exists in a table.

-Work Done: I automated browsing (with Splinter) which was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries, which was used to Analyze Mars Weather Data. I then extracted the HTML table into a Pandas DataFrame. The data was analyzed to answer "How many months exist on Mars?", "How many Martian days' worth of data are there?". The data was analyzed to answer the following questions, and a data visualization was created to support each answer: "Which month, on average, has the lowest temperature? The highest?", "Which month, on average, has the lowest atmospheric pressure? The highest?", "How many terrestrial days exist in a Martian year?" A visual estimate within 25% was made and the DataFrame was exported into a CSV file (Excel attached). 

-Conclusion:  

- On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
  
- Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
  
- The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
