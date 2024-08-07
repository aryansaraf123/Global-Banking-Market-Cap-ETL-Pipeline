# Top 10 largest Banks
This project demonstrates an ETL (Extract, Transform, Load) process on the top 10 largest banks by market capitalization.

## Overview
This project scrapes data from a Wikipedia page listing the largest banks by market cap, transforms the data into multiple currencies, and loads it into both CSV and SQLite database formats. The goal is to provide a clear and efficient ETL pipeline example.

## Repository Contents
- [banks_project.ipynb](banks_project.ipynb) : Jupyter Notebook with the complete ETL code.
- [Largest_banks_data.csv](Largest_banks_data.csv) : Contains the market cap of the top 10 banks in USD, GBP, EUR, and INR.
- [Banks.db](Banks.db) : SQLite database with the transformed data.
- [code_log.txt](code_log.txt) : Log file detailing the timestamps for each phase of the ETL process.

To best understand the project, please go through the files in the above order.

## Technologies Used
- Python (Jupyter Notebook)
- Libraries/Modules:
  - Pandas
  - Numpy
  - requests (optional)
  - BeautifulSoup (optional)
  - sqlite3
  - datetime

## Project Highlights
- Extraction: Data scraped from a [Wikipedia page](https://web.archive.org/web/20230908091635%20/https://en.wikipedia.org/wiki/List_of_largest_banks) using Pandas.
- Transformation: Market cap data converted into GBP, EUR, and INR.
- Loading: Data saved to both CSV and SQLite database formats.

## Data Insights
Explore the [Largest_banks_data.csv](Largest_banks_data.csv) and [Banks.db](Banks.db) to see the market cap data of the top 10 banks in various currencies. The [code_log.txt](code_log.txt) provides detailed logs of each phase of the ETL process, including timestamps.
