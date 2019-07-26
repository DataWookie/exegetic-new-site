---
title: "Plumber — Building an API"
topic: true
subjects: ['R']
subjects_weight: 120
draft: false
intro: |
  [Plumber](https://www.rplumber.io/) is a package which makes it possible to expose R functions as API endpoints. This makes building an API simple and fun.
duration: 1 day
who: Anybody who needs to put their R code or model into production.
objectives: |
  In this course you'll learn how to build an API which allows access to R functions and objects.
outcomes: |
  After the course participants will be able to
  
  - create an API from a collection of functions;
  - create informative documentation;
  - handle various types of input and output;
  - apply simple authentication; and
  - deploy the API in the cloud.
requirements: Participants should be familiar with R and comfortable writing their own functions.
---

- What is an API?
  - REST
  - Ways to access an API
    - Browser
    - [`curl`](https://curl.haxx.se/)
    - [Postman](https://www.getpostman.com/)
- Making a Quick API
  - Function decoration
  - Input and output
  - [Swagger](https://swagger.io/)
- Input
  - Types of endpoints (mostly `GET` and `POST` but also `PUT`, `DELETE` and `HEAD`)
  - Filters
  - Dynamic routing
  - Parameters
  - The request object
  - JSON input
- Output
  - The response object
  - Types of output (mostly JSON but also HTML, JPG, PNG and PDF)
  - Serving static files
  - Dealing with Errors
- Documentation
- Security
  - Cookies
  - Authentication with [{sealr}](https://github.com/jandix/sealr)
- Deploying an API
  - DigitalOcean and AWS
  - Docker
  - NGINX
