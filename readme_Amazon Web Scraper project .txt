Getting Started
****************************************************
Prerequisites
****************************************************

Python 3
requests library
beautifulsoup4 library
pandas library
****************************************************

Installation
****************************************************
You can install the required libraries using pip.

bash~ pip install requests beautifulsoup4 pandas
****************************************************
Usage
To use the scraper, simply run the amazon_scraper.py file using Python. This will scrape the data from the Amazon product page and save it to a CSV file named AmazonWebScraperDataset.csv.

The script can be modified to scrape data from a different Amazon product page by changing the URL variable at the top of the file.

The check_price function has been modified to calculate the price drop percentage based on the previous day's price. This data is also saved to the CSV file.

****************************************************
License

none
****************************************************