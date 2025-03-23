# DS2002-ETL-Project
Our ETL project correlating US Covid Cases (CSV) to Delta Airline Stock Prices (API call) 
Project Members: Aryana Bellamkonda, Mariana Mendez, Caroline Nguyen

# Correlating US COVID-19 cases to Delta Airlines’ Stock Prices

## Introduction 
This project analyzes the impact of US COVID-19 cases on Delta Airlines’ stock prices by merging stock market data from the Alpaca API with US COVID-19 cases csv data. The data is processed, transformed, and stored in multiple formats. 

## Required Libraries 
1. pandas
2. requests
3. sqlite3

## Instatllation 
1. Obtain an Alpaca API key.
   a. Sign up at [Alpaca](https://alpaca.markets/) and get an API key and secret key.
      - Sign up for a free account for a “Trading API.”
      - Locate “Home” tab and locate “API Keys” at bottom of page
      - In order to obtain a secret key, press “Regenerate”
   b. Replace API_KEY and API_SECRET in the script with your credentials.
2. Prepare COVID-19 dataset.
  a. Download [cumulative-deaths-and-cases-covid-19.csv](https://ourworldindata.org/grapher/cumulative-deaths-and-cases-covid-19) file and ensure it is in the same directory.
  b. In order to download the csv file from the website, click the download arrow, then go to the data tab, and finally download the full dataset. 
3. Run the script.
4. Choose the output format.
  a. The script will prompt you to select between csv, json, or sql.

## Usage
To use this project:
1. Run the script with Python, and follow the on-screen prompts to select an output format.
2. Analyze the correlation between COVID-19 cases and stock prices using the computed statistics.

## Example
Expected output:
Stock Data (Records, Columns): (X, Y)
COVID Data (Records, Columns): (X, Y)
Merged Data (Records, Columns): (X, Y)
Columns of Merged Dataset: [ ]
Correlation between closing price and total confirmed cases: R
Summary Statistics of Merged Data:
Enter desired output format (csv, json, sql) [default: sql]: (user’s choice) 
Data saved as user’s choice 

## License
This project is open-source and can be modified and used for research purposes.






