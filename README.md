# 📘🎧 Audible Web Scraper

## 📌 Overview
This project is a Python-based web scraper built using **Selenium**, designed to extract audiobook information from the Audible website using a **headless Chrome browser**. It navigates through multiple pages and collects structured data for further analysis.

### 🔍 Data Extracted
- **Title**
- **Subtitle**
- **Author** & **Narrator**
- **Duration** (converted to total minutes)
- **Release Date**
- **Language**
- **Rating** and **Rating Count**

---

## 🚀 Features
- Utilizes **explicit waits** to reliably capture dynamically loaded elements.
- Handles **dynamic pagination** to scrape data across all pages.
- Cleans and transforms raw text using **regular expressions** and **Pandas**.
- Exports the final structured dataset to a CSV file (`ebooks_data.csv`).

---

## 🧰 Libraries Used
- **Selenium**: Automates browser interactions and scrapes web elements.
- **Pandas**: Stores, manipulates, and exports data in tabular format.
- **re** (*Regular Expressions*): Cleans and parses text fields (e.g., durations, ratings).
- **time**: (Optional) Adds delays between interactions, although explicit waits are used instead.

---

## 🧠 What I Learned
***I learned the practical difference between **implicit** and **explicit waits** in Selenium. Implicit waits apply globally and may cause unnecessary delays, while explicit waits allow precise control by targeting specific conditions, improving scraping efficiency and reliability. Additionally, I learned how to implement **dynamic pagination** by iterating through pages and programmatically interacting with navigation elements. This project helped me strengthen my understanding of web automation, data extraction, and data cleaning using Python.***

---

## 📁 Output
The scraped data is saved as a CSV file:  
`ebooks_data.csv`

---
This project demonstrates practical skills in web automation, data extraction, and preprocessing for analysis or machine learning workflows.
Feel free to clone, explore, or extend this project!
