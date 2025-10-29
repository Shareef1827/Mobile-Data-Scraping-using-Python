# Mobile-Data-Scraping-using-Python

## Project Overview
This project focuses on automating the extraction of smartphone data such as brand, model, color, memory, battery capacity, and price from Flipkart using Python. The scraped data is structured, cleaned, and stored in CSV and Excel formats for analysis and comparison.

## Problem Statement
With the continuous release of new smartphones, manually comparing specifications and prices across multiple online platforms is tedious and time-consuming.
This project automates the process by scraping the latest mobile data and organizing it efficiently.

## Tools & Technologies
- Language: Python
- Libraries Used:
    - requests – to fetch webpage data
    - BeautifulSoup – to parse HTML content
    - re – for data cleaning using Regular Expressions
    - pandas – for data manipulation and export
- Output Files:
    - Mobiles Data.csv
    - Mobiles Data Excel.xlsx

## Key Steps
1. Fetch HTML data from Flipkart’s mobile listing page.
2. Extract key attributes:
- Brand and Model
- Price
- Color
- ROM and GB
- Display Size
- Battery Capacity
- Clean the extracted text using regular expressions.
- Create a DataFrame with structured columns.
- Export the data to CSV and Excel formats.

## Sample Output Columns
<img width="1238" height="677" alt="Photo" src="https://github.com/user-attachments/assets/89fda61c-8b6f-4a31-87c4-47dc8ef70110" />

## Future Enhancements
- Extend scraping to Amazon and Samsung official site.
- Include ratings, reviews, and camera specifications.
- Visualize trends using Power BI or Tableau.
- Automate data refresh using schedulers or APIs.

## Final Dataset Files
- <a href="https://github.com/Shareef1827/Mobile-Data-Scraping-using-Python/blob/main/Mobiles%20Data%20Excel.xlsx"> Mobiles Data Excel File </a>
- <a href="https://github.com/Shareef1827/Mobile-Data-Scraping-using-Python/blob/main/Mobiles%20Data.csv"> Mobiles Data CSV File </a>
