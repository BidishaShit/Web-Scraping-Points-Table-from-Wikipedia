# Web-Scraping-Points-Table-from-Wikipedia
# Overview
This Python script is designed to scrape the points table data from a Wikipedia page related to the 2023 Cricket World Cup. It utilizes the Selenium library for web scraping, along with other auxiliary libraries such as time, json.

# Functionality
The script defines a function named scrape_points_table which takes a URL of the Wikipedia page as input. Upon execution, the function performs the following steps:

1. Initializes a Chrome WebDriver instance.
2. Accesses the provided URL.
3. Waits for 2 seconds to allow the webpage to fully load.
4. Locates the points table on the webpage using XPath.
5. Iterates through each row of the table, extracting team names and their corresponding points.
6. Stores the extracted data in lists.
7. Combines team names and points into a dictionary.
8. Closes the WebDriver instance to free up system resources.
9. Returns the extracted data in JSON format.
# Prerequisites
Python 3.x installed on your system
Required Python library installed (Selenium)
