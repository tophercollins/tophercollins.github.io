# EIFO Data Extraction/Web Scraping > [Go to project](https://github.com/tophercollins/eifo-data-extraction)

This project involves building a Python script to extract country risk and cover policies from the EIFO website. The script utilizes BeautifulSoup for static HTML parsing and Selenium for handling dynamic website elements, with the data being cleaned and transformed in Pandas before exporting to an Excel output sheet.

## Problem Definition
The objective of this project is to automate the extraction of country risk and cover policies data from the EIFO website, which involves navigating dynamic web content. The extracted data is then cleaned, transformed, and stored in a structured format for further analysis or reporting.

## Data
The data extracted includes various country-specific risk factors and cover policies available on the EIFO website. The web pages were dynamically loaded, requiring the use of Selenium in conjunction with BeautifulSoup for effective data retrieval.

## Evaluation
Aim To successfully extract and structure the data in a manner that is suitable for further analysis or reporting, ensuring completeness and accuracy of the extracted data.

### Features
The dataset created from the extraction process contains multiple columns representing various attributes of the country risk and cover policies.

**Extracted Features:**
* Country Name
* Risk Category
* Cover Policy Type
* Additional Notes (if available)

### Exploratory Data Analysis
Before transformation, the data was reviewed to ensure the correctness and completeness of the extracted information. Pandas was used to clean and organize the data.

## Process
Web Scraping Setup: Initialized Selenium WebDriver to handle the dynamic loading of web pages on the EIFO site. Used BeautifulSoup for parsing the HTML content and extracting relevant data points.

Data Extraction: Implemented a scraping routine to iterate through the necessary web pages and extract relevant data points for each country.

Data Cleaning and Transformation: Loaded the extracted data into a Pandas DataFrame. Performed cleaning operations such as removing duplicates, handling missing values, and standardizing text fields.

Data Export: The cleaned and organized data was exported into an Excel file, ensuring it is in a format ready for analysis or reporting.

## Conclusion
This project successfully automated the extraction and organization of country risk and cover policies from the EIFO website. The final output was a structured Excel file, ready for further analysis. This approach significantly reduces the manual effort required to gather and process this information, ensuring up-to-date data availability.
