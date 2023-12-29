# Job Finder

## Overview

This Python project is designed to scrape job listings from popular job portals, including Naukri, Foundit, Shine, Indeed, and LinkedIn. Users can input the desired job title and location, and the script will extract detailed job information.

## Features

- **Multi-Portal Scraping:** Extracts job listings from Naukri, Foundit, Shine, Indeed, and LinkedIn.
- **Dynamic Page Interaction:** Utilizes Selenium for dynamic web page interaction.
- **HTML Parsing:** Uses BeautifulSoup for parsing HTML content.
- **Data Analysis:** Employs pandas for efficient data manipulation and analysis.
- **Rich User Interface:** Enhances user experience with the rich library for creating tables and color-coded output.
- **Option to Save Results:** Provides an option for users to save the scraped data locally in CSV format.

## Prerequisites

- **Python:** Ensure that Python is installed on your machine.
- **Dependencies:** Install project dependencies using `pip install -r requirements.txt`.
- **WebDriver:** Download and configure the appropriate WebDriver (e.g., ChromeDriver) for Selenium.

## Usage

1. Run the script by executing `python job_scraper.py`.
2. Enter the desired job title and location when prompted.
3. View the results displayed in a well-formatted table.
4. Optionally, choose to save the results locally when prompted.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Selenium](https://www.selenium.dev/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [pandas](https://pandas.pydata.org/)
- [rich](https://github.com/willmcgugan/rich)

