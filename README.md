## 1) Import Libraries:

requests: Used for making HTTP requests to fetch the content of web pages.
BeautifulSoup: A powerful library for web scraping. It helps in parsing HTML and extracting information from web pages in a structured way.
duckduckgo_search: Utilized to perform searches on DuckDuckGo search engine easily.

## 2) List of Queries:

Defined a list of queries that represent the information you want to gather. Each query is a specific aspect of the analysis related to the company "Canoo."

## 3) Function for Structured Response Extraction (BeautifulSoup):

Defined a function extract_structured_response(url) that uses BeautifulSoup to parse the HTML content of a given URL.
Extracted all paragraphs (<p> tags) from the page and joined them to create a structured response.
BeautifulSoup is chosen for its simplicity and flexibility in navigating and searching HTML content.

## 4) Initialize CSV File:

Opened a CSV file in write mode to store the results.
The CSV file is used to organize and save the extracted information for further analysis or reference.

## 5) DuckDuckGo Search (DDGS):

Utilized DuckDuckGo search engine through the DDGS class to perform searches based on the defined queries.
DuckDuckGo was chosen for its privacy-centric approach and simplicity in fetching search results programmatically.

## 6) Loop Through Queries:

Iterated through each query to gather information on different aspects of the company.

## 7) Loop Through Search Results:

For each query, obtained a list of search results from DuckDuckGo.
Iterated through the search results to extract URLs.

## 8) Structured Response Extraction and CSV Writing:

For each URL, called the extract_structured_response function to get structured information from the linked page.
Wrote the URL and the structured response to the CSV file for each search result.

## 9) Print Export Completion Message:

Printed a message indicating the successful export of data to the CSV file.
