# LinkedIn Web Scraper in Python

This repository contains a Python script for scraping LinkedIn profiles using Selenium. The script automates the process of logging in to LinkedIn, searching for specific user profiles, and extracting information such as name, job title, and location.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Selenium library (`pip install selenium`)
- Chrome WebDriver (compatible with your Chrome browser version)

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Download the Chrome WebDriver compatible with your Chrome browser version and place it in the project directory.
4. Open the `linkedin_scraper.py` file and replace `"Enter Your Email ID"` and `"Enter Password"` with your LinkedIn login credentials.
5. Customize the `user_name` variable with the name of the LinkedIn user you want to search for.
6. Run the script using the command `python linkedin_scraper.py`.
7. The script will log in to LinkedIn, search for the specified user profile, and scrape information from the top 10 search results. The data will be saved in a CSV file named `linkedin_profiles.csv`.

## Disclaimer

This script is intended for educational purposes only. Scraping LinkedIn data may violate LinkedIn's terms of service, so use it responsibly and respect the privacy of others.

Feel free to modify and customize this README according to your preferences and additional details about the project.
