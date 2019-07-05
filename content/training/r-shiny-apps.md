---
title: "Shiny — Building Data-Driven Apps"
topic: true
subjects: ['R']
subjects_weight: 120
draft: false
---

<!--
https://www.londonr.org/wp-content/uploads/sites/2/presentations/LondonR_-_Workshop-Introduction_to_Shiny_-_Aimee_Gott_-_20150330.pdf
https://uomresearchit.github.io/RSE18-shiny-workshop/
https://github.com/rstudio/webinars/tree/master/47-introduction-to-shiny
https://github.com/juliasilge/intro_to_shiny
https://github.com/Robinlovelace/learning-shiny
https://shiny.rstudio.com/tutorial/
https://deanattali.com/blog/building-shiny-apps-tutorial/
https://github.com/rstudio-education/intro-shiny-rmarkdown
https://shiny.rstudio.com/articles/debugging.html
-->

The Shiny package makes it easy to create interactive web applications using R.

## Details

**Duration** 2 days

**Who should attend?** The course is aimed at students, academics and professionals who want to build interactive web applications.

**Objectives**

An interactive web application is a great way to allow people to interact with data. The conventional approach to developing such an application requires knowledge of a range of web development tools. However, the Shiny package makes it possible to easily build a web application using only R. This allows you to focus on the data and user experience.

**Outcomes**

Participants will:

- understand the structure of a Shiny application (UI and server);
- be able to assemble an attractive UI;
- understand reactivity and how the UI and server communicate with each other; and
- know how to deploy a Shiny application.

**Requirements**

Participants are assumed to have prior exposure to R, or at least to programming of some variety. Ideally participants should have completed the [Data Wrangling]({{< ref "r-data-wrangling.md" >}}) and [Visualisation]({{< ref "r-visualisation.md" >}}) modules.

**Setup**

```r
install.packages(
  c("shiny", "rmarkdown", "DT", "devtools", "flexdashboard",
    "gapminder", "rticles", "shinydashboard", "shinythemes",
    "tidyverse", "tufte", "xaringan"),
  repos = "http://cran.rstudio.com"
)
```

## Contents

### Day 1

- What is Shiny?
  - Samples from App Gallery
- Components of a Shiny app
  - Simple example
- User Interface (UI)
  - Layouts
  - HTML formatting
  - Input controls
  - Panels and tabsets
- Server
  - Rendering output: text, plots and tables
  - `uiOutput()` for dynamic UI elements
- Reactivity
  - `reactive()`
  - `isolate()`
  - `eventReactive()`
  - `reactiveValues()`
- Interactive Components
  - [DataTable](https://datatables.net/)
  - [Leaflet](https://leafletjs.com/)
- Debugging
- Enhancements
  - CSS
  - Shiny themes
  - HTML widgets
  - Javascript

### Day 2

- Modules
- Testing
  - {shinytest}
  - {shinyloadtest}
- Deploying
  - [shinyapps.io](https://www.shinyapps.io/)
  - Shiny Server
- Scaling Shiny
  - [Shinyproxy](https://www.shinyproxy.io/)
  - [{golem}](https://github.com/ThinkR-open/golem)
