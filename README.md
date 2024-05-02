# NBA Player Career Stats Scraper

The NBA Player Career Stats Scraper is a Python script designed to automate the retrieval of career statistics for NBA players from the Basketball-Reference website. Leveraging the Selenium WebDriver, this project facilitates efficient data extraction by simulating user interactions with the web interface.

# Features:

## Automated Search and Navigation:

The script initiates by conducting a Google search for "hoops reference" and navigates to the Basketball-Reference link from the search results.

## Cookie Management:

Ensures a smooth user experience by automatically handling cookie pop-ups on both Google and Basketball-Reference websites.

## Player Selection:

Allows the user to specify an NBA player of interest, navigating through the Basketball-Reference site to select the player.

## Data Extraction:

Utilizes XPath and other locators to pinpoint key elements such as player names and career statistics on the webpage.

## Dynamic Waiting:

Implements WebDriverWait to dynamically wait for elements to load, ensuring the stability of the script across different page load times.

## Modular Design:

Organized into reusable functions for actions like denying cookies, waiting for elements, and player selection, promoting code modularity and maintainability.

# Usage:

## Setup:

Ensure you have the required dependencies installed, including Selenium and the ChromeDriver executable.
Adjust the chromedriver.exe path in the script to match your system.

## Run the Script:

Execute the script, and it will perform automated interactions, from initiating a Google search to displaying the career statistics of the specified NBA player.

## Customization:

Modify the script to interact with different NBA players by adjusting the player's XPath or other locators as needed.

## Dependencies:
Selenium (https://selenium-python.readthedocs.io/): Python library for browser automation.
ChromeDriver (https://chromedriver.chromium.org/downloads): WebDriver for the Chrome browser (it has to be exactly the same edition with google chrome).


