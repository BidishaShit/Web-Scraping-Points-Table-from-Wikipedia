# Web-Scraping-Points-Table-from-Wikipedia
# Overview
This Python script is designed to scrape the points table data from a Wikipedia page related to the 2023 Cricket World Cup. It utilizes the Selenium library for web scraping, along with other auxiliary libraries such as time, json.

# Functionality
The script defines a function named scrape_points_table which takes a URL of the Wikipedia page as input. Upon execution, the function performs the following steps:

1. The script uses Selenium WebDriver to automate web browsing and extract data from the Wikipedia page.
2. It locates the points table on the page using XPath.
3. It then iterates through each row of the table, extracting the team name and points.
4. The data is stored in a list of dictionaries.
5. Finally, the WebDriver is closed, and the data is returned in JSON format.
# Prerequisites
1. Python 3.x installed on system
2. Required Python library installed (Selenium)
