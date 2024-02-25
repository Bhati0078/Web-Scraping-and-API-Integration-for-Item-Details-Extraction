# Web-Scraping-and-API-Integration-for-Item-Details-Extraction

# Overview :
This project focuses on extracting item details from a web platform utilizing a combination of web scraping with Selenium and API integration. The extracted data is then organized into a structured format and saved to an Excel file for further analysis.

# Key Features :
Web Scraping with Selenium: The script navigates through web pages, specifically targeting widgets of type 'sync' and view type 'reco'. It extracts relevant item details from these widgets, such as ID, name, brand, category, rating, discount, EAN code, features, image URL, price, offer price, stock status, total rating, like count, review count, default seller information, and max order quantity.

# API Integration : 
The script seamlessly integrates with an API to fetch additional item details, enhancing the richness of the dataset.

# Data Organization : 
Extracted data is compiled into a structured list of items and subsequently transformed into a Pandas DataFrame. This DataFrame is then saved as an Excel file ('item_details.xlsx').

# Usage :
Clone the repository to your local machine.
Ensure you have the required dependencies installed (Selenium, Pandas).
Execute the script to perform web scraping and API integration.
Find the extracted item details in the 'item_details.xlsx' Excel file.

# Dependencies :
Selenium: For web automation and scraping.

Pandas: For data manipulation and organization.
