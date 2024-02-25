# Web-Scraping-and-API-Integration-for-Item-Details-Extraction
# Overview:
This Python script performs web scraping through an API to extract detailed information about items from the 'widgets' endpoint in the response. The extracted data includes various attributes such as ID, name, brand, category, average rating, discount, EAN code, features, image URL, price, offer price, stock status, total rating, like count, review count, default seller details, and maximum order quantity.

# Functionality:
The script iterates through the widgets, filters items based on type and view type criteria, and compiles the extracted details into a structured list. This list is then used to create a Pandas DataFrame for easy manipulation and analysis. The DataFrame is subsequently saved as an Excel file named "item_details.xlsx".

# Dependencies:
Python 3.x
Pandas library
Json
# Note:
Make sure to handle the web scraping ethically and in compliance with the terms of service of the website being scraped.
