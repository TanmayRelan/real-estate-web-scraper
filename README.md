# Real-estate-web-scraper

## Project Description
This project demonstrates a web scraping tool developed to extract and analyze rental property data from Square Yards for the city of Nashik. The goal was to automate the extraction of detailed rental listings to aid in market analysis and property research. This tool captures a range of property details including title, price, deposit, listing type, property type, locality, area, furnishing status, number of rooms, number of bathrooms, number of parking spots, floor number, and security deposit.

## Key Features
- **Automated Data Extraction**: Scrapes rental property listings from Square Yards, reducing manual data collection efforts.
- **Comprehensive Data Collection**: Extracts multiple property attributes, providing a holistic view of rental options.
- **CSV Output**: Saves the extracted data into a CSV file for easy manipulation and analysis in spreadsheet software.

## Technologies Used
- **Python**: The programming language used for writing the script.
- **BeautifulSoup**: For parsing HTML content and extracting data.
- **Requests**: For making HTTP requests to fetch web pages.
- **Pandas**: For handling data and exporting it to CSV format.

## Functions
- **get_title(soup)**: Retrieves the property title.
- **get_price(soup)**: Retrieves the property price.
- **get_deposit(soup)**: Retrieves the deposit amount.
- **get_listing_type(soup)**: Retrieves the type of listing.
- **get_property_type(soup)**: Retrieves the type of property.
- **get_locality(soup)**: Retrieves the locality.
- **get_area(soup)**: Retrieves the area of the property.
- **get_furnishing_status(soup)**: Retrieves the furnishing status.
- **get_number_of_room(soup)**: Retrieves the number of rooms.
- **get_number_of_bathroom(soup)**: Retrieves the number of bathrooms.
- **get_number_of_parking(soup)**: Retrieves the number of parking spots.
- **get_floor_no(soup)**: Retrieves the floor number.
- **get_security_deposit(soup)**: Retrieves the security deposit.
