---
title: "Web Scraping"
topic: true
subjects: ['Python', 'Web Scraping']
subjects_weight: 80
draft: false
intro: |
  There's a wealth of data available on the internet which can be used for data augmentation or to create entirely new datasets.
duration: 2 days
objectives: |
  In this course you'll learn how to use Python to selectively, systematically and automatically scrape data from websites.
outcomes: |
  You'll know

  - the basics of HTML and CSS;
  - how to parse an HTML document and extract data using [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/);
  - how to build a spider to traverse an entire website using [Scrapy](https://scrapy.org/);
  - how to drive a browser using Selenium and Python bindings; and
  - how to store scraped data as CSV or JSON.
requirements: |
  You are assumed to have have experience with Python. Familiarity with HTML and CSS will be an advantage.
setup: |
  - Get a recent version of [Google Chrome](https://www.google.com/chrome/browser/) or [Firefox](https://www.mozilla.org/en-US/firefox/).
    - Install the [SelectorGadget extension](http://selectorgadget.com/).
  - Get a recent version of Python.
    - Install the following packages: `requests`, `numpy`, `pandas`, `beautifulsoup4` and `selenium`.
  - Install a VNC client. 
     - [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/) (Windows, MacOS and Linux)
     - [vinagre](https://wiki.gnome.org/Apps/Vinagre) or xtightvncviewer (Linux)
  - Install [Docker](https://www.docker.com/) and pull the following images:
    - `selenium/standalone-firefox:3.14`
    - `selenium/standalone-chrome-debug:3.14`
  - Go through this [fun CSS tutorial](http://flukeout.github.io/).
---

- Introduction to Web Scraping
  - Structure of a web page
  - Selectors
      - CSS
      - XPath
  - Browser tools
- HTTP
  - Requests
  - Status codes
- [requests](http://docs.python-requests.org/en/master/)
  - GET request
  - The response
      - Status code
      - Headers
      - Content
  - Query strings
  - Request headers
  - Authentication
  - Performance
  - Timeouts
  - Sessions
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) &mdash; Parsing HTML
  - `BeautifulSoup` object
  - `Tag` object
  	  - Name
  	  - Text
  	  - Attributes
  - Navigating HTML
  	  - Using tag names
      - `select()` and `select_one()`
      - Parents, siblings, descendants and children
      - Various forms of `find()`
- [Selenium](https://selenium-python.readthedocs.io/) &mdash; Scraping dynamic sites
  - Selenium on Docker
      - Chrome
      - Firefox
      - Debug images and VNC connections
  - Navigation
  - Locating elements
  - Waiting (explicit and implicit waits)
  - Screenshots
  - Cookies
- [Scrapy](https://scrapy.org/) &mdash; Creating a Spider
  - What is a spider?
  - Scrapy shell
  - Project
  - Writing spiders
      - `Spider` class
      - Selectors
      - Navigation
      - Gathering links
      - Extracting and storing data
      - Following links and recursion
  - Spider patterns
      - Using `sitemap.xml`
  - Using Selenium
{{< comment >}}
- [Mechanize](https://github.com/python-mechanize/mechanize)
  - TBA
{{< /comment >}}