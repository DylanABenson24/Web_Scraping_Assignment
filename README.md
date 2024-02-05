# Web Scraping Assignment

This assignment demonstrates web scraping using Python, BeautifulSoup, and Pandas libraries. The goal of the assignment is to scrape data from a given webpage and store it into a structured format.

## Getting Started
### Requirements

- Python 3.x
- Jupyter Notebook
- Beautiful Soup
- Requests
- Pandas

## Installing
#### To install the necessary libraries, run the following command:

```pip install beautifulsoup4 requests```

## Usage
Clone the repository to your local machine.
Install the required libraries using pip.
Run the Jupyter Notebook file.

### Web Scraping Basics
This notebook covers the basics of web scraping using Beautiful Soup and Requests. It includes methods to extract data from HTML pages and work with HTML tags.
The notebook demonstrates two methods for scraping data from an HTML table:

Method 1:

- The URL to scrape is defined.
- A GET request is sent to the URL and the response is printed.
- The HTML content of the page is parsed using BeautifulSoup.
- The table on the webpage is found and printed.
- The headers in the table are found and placed in a list called "titles".
- An empty Pandas DataFrame is created with the column names equal to the table headers in the list "titles".
- The rows in the table are found and placed into an object called "rows".
- The data cells are extracted from the rows and appended to the corresponding columns in the DataFrame.

Method 2:

- A string that simulates an HTML page with a table is created.
- A soup object is created using the html.parser.
- The table in the soup object is found and printed.
- The headers in the table are found and placed in a list called "titles".
- An empty Pandas DataFrame is created with the column names equal to the table headers in the list "titles".
- The rows in the table are found and placed into an object called "rows".
- The data cells are extracted from the rows and appended to the corresponding columns in the DataFrame.

## Notes
When scraping websites, always make sure to respect the website's terms of service and robots.txt file.
This repository is for educational purposes only.

## Built With
Beautiful Soup 4 - HTML and XML parsing library
Requests - HTTP library

## License
This project is licensed under the MIT License.

## Authors
Dylan Benson
