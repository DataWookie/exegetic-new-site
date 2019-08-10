---
title: "Web Scraping with R"
topic: true
subjects: ['R', 'Web Scraping']
subjects_weight: 130
intro: |
  There's a wealth of data available on the internet which can be used for data augmentation or to create entirely new datasets.
duration: 2 days
who: |
  The course is aimed at students, academics and professionals who need to harvest data from the internet.
objectives: |
  In this course you'll learn how to use R to selectively scrape content from websites.

  During this course we'll scrape data from a number of sites including:

  - browser market share from [StatCounter](http://gs.statcounter.com/browser-market-share);
  - weather data from [Weather Underground](https://www.wunderground.com/).
outcomes: |
  Participants will be able to isolate the relevant portions of a website and write scripts to automatically extract the required information. Furthermore they'll know how to apply these techniques to both static and dynamic websites.
requirements: |
  Participants are assumed to have prior exposure to R and the `{dplyr}`, `{purrr}` and `{stringr}` packages. Some familiarity with HTML and CSS will be an advantage but not mandatory.
setup: |
  - Get a recent version of [Google Chrome](https://www.google.com/chrome/b/) or [Firefox](https://www.mozilla.org/en-US/firefox/).
    - Install the [SelectorGadget extension](http://selectorgadget.com/).
  - Get a recent version of [R](https://cran.r-project.org/) (3.6.0 or newer) and [RStudio Desktop](https://www.rstudio.com/products/rstudio/download/).
    - Install the following R packages: `rvest`, `RSelenium`, `splashr` and `tidyverse`.
  - Install a VNC client. 
     - [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/) (Windows, MacOS and Linux)
     - [vinagre](https://wiki.gnome.org/Apps/Vinagre) or xtightvncviewer (Linux)
  - Install [Docker](https://www.docker.com/) and pull the following images:
    - `selenium/standalone-firefox:3.14`
    - `selenium/standalone-chrome-debug:3.14`
---

### Day 1

- Motivating Example
- Review of the Tidyverse
	- Highlights from [Data Wrangling]({{< ref "r-data-wrangling.md" >}})
- Website screenshots
- Navigating the Internet with URLs
	- Anatomy of an URL
	- Building URLs with `{urltools}`
	- Encoding and decoding parameters
- HTTP
	- How HTTP works
	- Diagnosing requests with `curl` and <https://httpbin.org/>
- Introduction to Scraping
	- The components of an HTML document
	- Building a simple HTML document
	- DOM
	- CSS (summary of [CSS]({{< ref "web-css.md" >}}))
	- XPath (summary of [XPath]({{< ref "web-xpath.md" >}}))
	- Developer Tools
	- Important files: `robots.txt` and `sitemap.xml`
	- Ethics
- Manual Scraping
	- Using [RCurl](https://cran.r-project.org/web/packages/RCurl/index.html) and [XML](https://cran.r-project.org/web/packages/XML/index.html).
- Scraping a Static Website using [rvest](https://github.com/hadley/rvest)
	- Retrieving page content
	- Navigation
	- Extracting text
	- Extracting attributes
	- Working with tables
	- Storing data as CSV or JSON.
	- Case Study
- Assisted Assignment <!-- IMDB -->

### Day 2

- Case Study <!-- drug tests using rvest -->
- Sessions
	- Moving around with `jump_to()`
	- Checking session history
	- Filling forms
- Dynamic Websites and JavaScript
	- Using [splashr](https://github.com/hrbrmstr/splashr) for JavaScript.
- Driving a Browser using [RSelenium](https://github.com/ropensci/RSelenium)
	- Why is RSelenium needed?
	- Navigation
	- Interacting with elements
	- Combining RSelenium with rvest
	- Useful JavaScript tools
	- Going headless
	- Case Study
- Building Robust Scrapers
	- Handling errors using `tryCatch()`
	- Functional tools from purrr: mapping, walking, `insistently()` and `slowly()`
- Deploying a Scraper in the Cloud
	- Launching and connecting to an EC2 instance
	- Headless browsers
	- Automation with cron

<!--
- Interacting with APIs
	- Using XHR to find an API
	- Building wrappers around APIs
-->