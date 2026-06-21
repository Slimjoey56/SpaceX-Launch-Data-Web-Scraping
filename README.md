# SpaceX-Launch-Data-Web-Scraping
Python web scraping project that extracts SpaceX launch data from Wikipedia using Requests and BeautifulSoup. The workflow parses HTML tables, cleans and structures launch details including payloads, orbits, customers, booster versions, and outcomes into a Pandas DataFrame for analysis and machine learning applications. 

# SpaceX Launch Data Web Scraping Project

## Overview

This project demonstrates how to collect, clean, and structure SpaceX launch data through web scraping using Python. Data was extracted from the SpaceX launch records available on Wikipedia and transformed into a structured dataset for further analysis and machine learning applications.

The project focuses on building practical skills in HTTP requests, HTML parsing, data extraction, and data preparation using industry-standard Python libraries.

## Objectives

* Retrieve web content programmatically using HTTP requests
* Parse HTML documents with BeautifulSoup
* Extract relevant launch information from HTML tables
* Clean and organize scraped data into a structured format
* Create a Pandas DataFrame for exploratory data analysis and predictive modeling

## Dataset Features

The final dataset includes the following attributes:

* Flight Number
* Launch Date
* Launch Time
* Booster Version
* Launch Site
* Payload
* Payload Mass
* Orbit
* Customer
* Launch Outcome
* Booster Landing Result

## Technologies Used

* Python
* Jupyter Notebook
* Requests
* BeautifulSoup4
* Pandas
* NumPy

## Project Workflow

1. Send an HTTP request to the SpaceX Wikipedia page.
2. Parse the HTML content using BeautifulSoup.
3. Identify and extract launch tables.
4. Process table headers and rows.
5. Clean and standardize the extracted data.
6. Store the results in a Pandas DataFrame.
7. Export the dataset for downstream analysis.

## Key Learning Outcomes

* Web scraping fundamentals
* HTML document structure and parsing
* Data cleaning and preprocessing
* Working with nested HTML elements
* Converting unstructured web data into tabular datasets

## Repository Structure

```text
├── data/
│   └── spacex_launch_data.csv
├── notebooks/
│   └── jupyter-labs-webscraping.ipynb
├── images/
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spacex-web-scraping.git
cd spacex-web-scraping
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Example Usage

Run the notebook:

```bash
jupyter-lab notebooks/jupyter-labs-webscraping.ipynb
```

## Future Improvements

* Automate data updates with scheduled scraping
* Integrate data from the SpaceX API
* Perform exploratory data analysis and visualization
* Build predictive models for launch success

## Acknowledgments

* IBM Data Science Professional Certificate
* SpaceX
* Wikipedia contributors
* BeautifulSoup documentation
