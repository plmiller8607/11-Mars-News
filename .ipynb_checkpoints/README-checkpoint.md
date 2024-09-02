# 11-Mars-News & Weather Challenge

Overview
This is a full web-scraping and data analysis project. After identifying HTML elements, id and class attributes on the https://static.bc-edx.com/data/web/mars_news/index.html web page, information is extracted via both automated browing with Selenium and HTML parsing with Beautiful Soup. This information will be scraped from various elements including HTML tables and multiple news articles on the web page.


Resources
Jupyter notebook Mars news and weather files
CSV file for Mars weather data


Usage
Use Selenium to visit the website
Use Beautiful Soup to extract the HTML code
Scrape titles and preview the text and store as a list of dictionaries
Extract HTML table into a Pandas DataFrame and scrape the data
Perform specific data analytics using the DataFrame
Export the DataFram into a CSV.file


Dependencies
Pandas
Matplotlib
Selenium
BeautifulSoup
ChromeDriverManager
Webdriver


License
This project is licensed under the MIT License - see the LICENSE file for details.
