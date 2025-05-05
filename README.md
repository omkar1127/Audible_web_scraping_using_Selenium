## Audible Web Scraper 📘🎧

This project is a Python-based web scraper built using **Selenium**, designed to extract audiobook information from the Audible website in a headless Chrome browser. 
The scraper navigates through multiple pages, collecting key data such as:

- **Title**
- **Subtitle**
- **Author & Narrator**
- **Duration** (converted to total minutes)
- **Release Date**
- **Language**
- **Ratings and Rating Count**

### Features
- Uses **explicit waits** to ensure elements are loaded before scraping.
- Handles **pagination** to scrape data from all available pages.
- Cleans and transforms data using **regular expressions** and **Pandas**.
- Outputs the structured dataset to a CSV file (`ebooks_data.csv`).

### Libraries Used
- Selenium : For automating browser interactions and scraping web elements.
- Pandas : To store, manipulate, and export the scraped data in tabular form.
- re (Regular Expressions) : For cleaning and transforming text data (e.g., stripping numbers from titles, parsing durations and ratings).
- time : Used for adding delays between requests, although you used explicit waits instead.

## Things that i learn From this projects:
***I learned the practical difference between implicit and explicit waits in Selenium. 
Implicit waits apply globally and may lead to unnecessary delays, 
while explicit waits allow precise control by targeting specific conditions, 
making scraping more efficient and reliable. 
Additionally, I learned how to handle dynamic pagination by iterating through pages and interacting with navigation elements programmatically.***

This project demonstrates practical skills in web automation, data extraction, and preprocessing for analysis or machine learning workflows.

