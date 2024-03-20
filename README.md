# Web-Scraping-Points-Table-from-Wikipedia
# Overview
This Python script is designed to scrape the points table data from a Wikipedia page related to the 2023 Cricket World Cup. It utilizes the Selenium library for web scraping, along with other auxiliary libraries such as time, json, and pandas.

# Functionality
The script defines a function named scrape_points_table which takes a URL of the Wikipedia page as input. Upon execution, the function performs the following steps:

Initializes a Chrome WebDriver instance.
Accesses the provided URL.
Waits for 2 seconds to allow the webpage to fully load.
Locates the points table on the webpage using XPath.
Iterates through each row of the table, extracting team names and their corresponding points.
Stores the extracted data in lists.
Combines team names and points into a dictionary.
Closes the WebDriver instance to free up system resources.
Returns the extracted data in JSON format.
# Prerequisites
Python 3.x installed on your system
Required Python library installed (Selenium)
