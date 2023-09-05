## Webscrape Real Estate Data 

This project is an ETL pipeline that extracts real estate data from a website, transforms the data, performs data analysis in a Jupyter Notebook, and loads it to a Postgresql database.

**Extract** - 
Real estate website is requested and each page is navigated using Selenium. BeautifulSoup is utilized to scrape the data.

**Transform** - 
The data is stored a dataframe and transformed into the appropriate format. 

**Data Analysis**
Data analysis is performed on the data using matplotlib and seaborn libraries.

**Load** -
The transformed data is loaded to a Postgresql database and also converted to a csv file.
