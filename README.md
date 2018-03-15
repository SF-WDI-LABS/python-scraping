# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Working With API Data

> Unit 4: Required

---

## Materials We Provide

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Part 1: APIs | [Here](./api-scraping.ipynb) |
| Lesson | Part 2: Webscraping | [Here](./webscraping.ipynb) |

> Please note: This lesson makes use of datasets from the `requests` library. The webscraping-ii module requires `selenium` and `geckodriver` and is best taught using Google Chrome.

---

## Learning Objectives

#### Part 1: Intro to Web Services & APIs
_After this lesson, students will be able to:_
- Identify relevant HTTP Verbs & their uses.
- Describe Application Programming Interfaces (APIs) and know how to make calls and consume API data.
- Access public APIs and get information back.
- Read and write data in JSON format.
- Demonstrate how to use the `requests` library.

#### Part 2: Webscraping in Class
_After this lesson, students will be able to:_
- Revisit how to locate elements on a webpage
- Aquire unstructured data from the internet using `BeautifulSoup`.
- Discuss limitations associated with simple requests and urllib libraries

---

## Student Requirements

Before this lesson(s), students should already be able to:
- Interpret and use Python dictionaries
- Build Pandas DataFrames from dictionaries
- Perform simple data manipulation on Pandas objects\
- Build `for` and `while` loops in Python
- Use `pip install` for package management

---

## Lesson Outline

### Outline: Part 1 (APIs)

- Introduction to APIs
- What is an API?
- Web APIs
- Making API calls
- HTTP
- Independent practice: HTTP
- HTTP Request
    - HTTP Request methods
    - HTTP Request structure
- HTTP Response
    - Response types overview
- JSON
- Guided practice: pulling data from APIs
    - Example: Star Wars
- Closing questions


### Outline: Part 2 (Web Scraping in Class)

- Introduction to Web Scraping
- Building a web scraper
- Retrieving data from the HTML page
    - Retrieving the restaurant names
    - Challenge: Retrieving the restaurant locations
    - Retrieving the restaurant prices
    - Retrieving the restaurant number of bookings
- Summary

---

## Installation Notes

When running this lesson, please check the following environment requirements:
1. Have Beautiful Soup installed: ```pip install bs4```

---

## Additional Resources

For more information on this topic, check out the following resources:

- Using `selenium` to scrape rendered text: [Selenium docs](http://selenium-python.readthedocs.io/locating-elements.html#locating-elements)
- Using Selenium to enter website information: [demo](http://thiagomarzagao.com/2013/11/12/webscraping-with-selenium-part-1/)
- Python regex tester: [here](http://pythex.org/)
