Flipkart Mobile Phones Web Scraper
Overview
A comprehensive web scraping project that extracts mobile phone data from Flipkart's search results for devices priced under 50,000 INR. This project demonstrates proficiency in web scraping, data cleaning, and data analysis using Python.
Dataset Size: 9,072 mobile phone listings
Data Points: Product name, price, specifications, ratings

Project Description
This project automates the collection of mobile phone product information from Flipkart's e-commerce platform. It extracts structured data including product names, prices, detailed specifications, and customer ratings for subsequent analysis.
Key Features

Web scraping using BeautifulSoup and Requests
Dynamic pagination handling (380+ pages)
HTML parsing and data extraction from complex DOM structures
Data cleaning and normalization
CSV export for data analysis
Handles real-world web scraping challenges (headers, parsing, data formats)


Data Collected
The scraper collects the following information for each phone:

Product Name - Device model and variant details
Price - Listed price in Indian Rupees (including currency symbol)
Specifications - RAM, ROM, display size, screen type, expandable storage
Rating - Customer rating on Flipkart (0-5 scale)
Technologies Used
Libraries

Pandas - Data manipulation and CSV export
BeautifulSoup4 - HTML parsing and DOM traversal
Requests - HTTP requests with custom headers
LXML - Fast XML/HTML processing

Tools

Python 3.x
Jupyter Notebook
Git
Dataset Analysis Potential
This dataset enables analysis across multiple dimensions:
Price Analysis

Price distribution across brands
Average pricing by RAM/ROM configuration
Price vs. rating correlation

Brand Insights

Market share by number of listings
Brand rating comparisons
Price positioning by manufacturer

Specifications Trends

Popular RAM/ROM combinations
Display size preferences
Storage expandability options

Customer Satisfaction

Rating distribution analysis
Rating vs. price relationships
High-rated budget phones identification
