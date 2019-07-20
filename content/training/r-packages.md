---
title: "Building R Packages"
topic: true
subjects: ['R']
subjects_weight: 24
draft: true
intro: |
  An R package is simply a group of related functions. Packages make it easier to organise and share code. It sounds complicated, but it's not.

  In this training you'll learn how to use RStudio and a selection of packages, like `{devtools}` and `{usethis}`, to create your own packages.
duration: 1 day
who: Anybody who writes their own functions in R will benefit from knowing how to wrap those functions up in a package.
objectives: |
  In this course you'll learn how to turn a collection of functions into a package.
outcomes: |
  After the course participants will be able to
  
  - set up the infrastructure for a package;
  - add functions and documentation;
  - create unit tests;
  - build the package; and
  - share the package via GitHub.
requirements: Participants should be familiar with R and comfortable writing their own functions.
---

## Course Outline

- Why Write R Packages?
- A Simple Package
    - The anatomy of a package
        - Metadata: `DESCRIPTION` and `NAMESPACE`
        - Folders: `R/`, `man/` and `data/`
    - Creating package infrastructure
    - Adding a function
    - Creating documentation
    - Adding data
    - Building the package
- Tests
    - The importance of tests
    - Writing simple tests with [{testthat}](https://github.com/r-lib/testthat)
    - Running tests and interpreting results
    - Test driven development
- Distribution
    - GitHub
    - Creating a package website with [{pkgdown}](https://pkgdown.r-lib.org/)
    - Testing revisited: Continuous Integration with [Travis](https://travis-ci.org/)
    - Preparing for CRAN