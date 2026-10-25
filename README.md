# Ceneo review scraper & parser

A Python-based web scraping tool designed to automatically extract and parse product reviews from the Ceneo e-commerce platform.

## Features

* **Multi-page crawling:** Dynamically handles pagination to iterate through all review pages for a given product.
* **Structured data extraction:** Parses key metadata using BeautifulSoup:
  * Review ID, Author, and Content text
  * Numerical star score and Recommendation status (*Polecam* / *Nie polecam*)
  * Categorized **Pros** and **Cons**
  * Usefulness votes count (*Useful* / *Unuseful*)
  * Publication date and Verified Purchase timestamp
* **Error Handling:** Robust handling for optional HTML fields and missing tags.

## Tech stack

* **Python**
* **BeautifulSoup** — HTML parsing and DOM navigation
* **Requests** — HTTP requests
* **Jupyter Notebook** —  code execution and testing
