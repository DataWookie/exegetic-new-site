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
    - Listing `installed.packages()`
    - Loading a package: `library()` versus `required()`
    - Installing
        - CRAN
        - GitHub
- A Simple Package
    - The anatomy of a package
        - `README.md`
        - Metadata: `DESCRIPTION` and `NAMESPACE`
        - Folders: `R/`, `man/`, `data/` and `tests/`
    - Creating package infrastructure
    - Adding a function
    - Creating documentation
    - Adding data
    - Building
    - Installing
        - Where? Understanding `.Library` and `.libPaths()`.
- Documentation
    - Documenting functions with [{roxygen2}](https://github.com/klutometis/roxygen)
    - Creating a package website with [{pkgdown}](https://pkgdown.r-lib.org/)
- Tests
    - The importance of tests
    - Writing simple tests with [{testthat}](https://github.com/r-lib/testthat)
    - Running tests and interpreting results
    - Test driven development
- Automation
    - Package setup with [{usethis}](https://usethis.r-lib.org/)
        - `create_package()`
        - `use_r()` and `use_test()`
        - `use_git()` and `use_github()`
    - Coding workflow with [{devtools}](https://github.com/r-lib/devtools)
        - `load_all()`
        - `document()`
        - `check()`
        - `build()` and `install()`
- Distribution
    - GitHub
    - Testing revisited: Continuous Integration with [Travis](https://travis-ci.org/)
    - Preparing for CRAN
