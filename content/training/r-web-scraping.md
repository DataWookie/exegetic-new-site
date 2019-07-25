---
title: "Web Scraping"
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

  - postal codes from [GeoNames](http://www.geonames.org/);
  - browser market share from [StatCounter](http://gs.statcounter.com/browser-market-share);
  - weather data from [Weather Underground](https://www.wunderground.com/).
outcomes: |
  Participants will be able to isolate the relevant portions of a website and write scripts to automatically extract the required information. Furthermore they'll know how to apply these techniques to both static and dynamic websites.
requirements: |
  Participants are assumed to have prior exposure to R, or at least to programming of some variety. Some familiarity with HTML and CSS will be an advantage but not mandatory.
---

### Day 1

- Motivating Example <!-- Private Property -->
- Review of the Tidyverse
	- Highlights from [Data Wrangling]({{< ref "r-data-wrangling.md" >}})
- Introduction to Scraping
	- The components of an HTML document
	- Building a simple HTML document
	- DOM
	- CSS (summary of [CSS]({{< ref "web-css.md" >}}))
	- XPath (summary of [XPath]({{< ref "web-xpath.md" >}}))
	- Developer Tools
	- Important files: `robots.txt` and `sitemap.xml`
	- Ethics
- HTTP
	- How HTTP works
	- Diagnosing requests with `curl` and <https://httpbin.org/>
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
- Interacting with APIs
	- Using XHR to find an API
	- Building wrappers around APIs
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