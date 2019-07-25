---
title: "Markdown & Automated Reporting"
topic: true
subjects: ['R']
subjects_weight: 100
draft: true
intro: |
  Do you spend a lot of time generating reports? Do you end up regenerating tables and figures when new data become available? Is this a complicated and error-prone process? If so, then this course is for you!

  Automating your reporting process will save you time and reduce errors.
duration: 1 day
who: The course is aimed at students, academics and professionals who need to generate data-driven reports.
objectives: Reports are an important artefact of research and analysis. Often these reports need to be frequently generated or updated. Ideally this should be done in a reproducible manner. It's is an ideal opportunity for automation! In this course you'll learn how to use R and Markdown to efficiently generate sophisticated and visually appealing reports.
outcomes: Participants will be able to generate reports which include text, tables, figures, code and analytical results. They will also be able to flexibly style the reports.
setup: |
  - Participants are assumed to have prior exposure to R, or at least to programming of some variety. Ideally participants should have completed the [Data Wrangling]({{< ref "r-data-wrangling.md" >}}) and [Visualisation]({{< ref "r-visualisation.md" >}}) modules.
  - Install a Markdown editor. These are some options:

    - [Remarkable](https://remarkableapp.github.io/index.html)
    - [MarkdownPad](http://markdownpad.com/)

      If all else fails you can use the [Dillinger](https://dillinger.io/) online editor.
---

<!--
https://github.com/rstudio/rstudio-conf/tree/master/2017/Advanced%20R%20Markdown%20-%20Yihui%20Xie
https://github.com/rstudio/rstudio-conf/tree/master/2018/Multilingual_Rmarkdown--Aaron_Berg
https://github.com/rstudio/rstudio-conf/tree/master/2018/R_Markdown_Eight_Ways--Mine_Cetinkaya_Rundel
https://github.com/rstudio-education/intro-shiny-rmarkdown
-->

<!--
https://www.cultureofinsight.com/blog/2018/10/22/2018-08-20-automated-data-reports-with-r/
-->

<!--
1. Introduction to Markdown
2. Creating R Markdown documents in RStudio
    - Code chunks
    - Code chunk options
3. Building documents from a script
4. Sending documents via email
5. Automation with `cron`
5. Case study: Automated reporting of Cryptocurrency transactions
6. Build your own report
-->

<!--
- Data Ingestion
  - Loading data from flat files
  - Database queries
- Data Preparation
  - Wrangling data with [dplyr](https://github.com/tidyverse/dplyr)
  - Pivoting data with [tidyr](https://github.com/tidyverse/tidyr)
- Figures and Tables
  - Generating plots with [ggplot2](https://github.com/tidyverse/ggplot2)
  - Building tables
- Styling Reports
- Dissemination
  - Emailing reports
- Twitter
- Slack
- Telegram
- Deploying
  - Scheduling report generation
-->

- What is Mark(up|down)?
  - What's different about [R Markdown](https://github.com/rstudio/rmarkdown)?
- Why Markdown?
  - Why not Word or Google documents?
- First Markdown File
- Markdown Structure
  - Paragraphs
  - Headings
  - Emphasis
  - Lists and Checkboxes
  - Links
  - Images
  - Block quotes
  - Footnotes
- YAML Header
  - Output formats
- Code
  - Code blocks
  - Including code and/or output (or neither!)
  - Inline code
- Generating References and a Bibliography
- Topics:
  - Presentations
    - slidy
    - [xaringan](https://github.com/yihui/xaringan)

<!--
  - Building Dashboards with [flexdashboard](https://github.com/rstudio/flexdashboard)
  - Writing a Book with [bookdown](https://github.com/rstudio/bookdown)
  - Creating a Blog with [blogdown](https://github.com/rstudio/blogdown)
  - Making Interactive Tutorials with [learnr](https://github.com/rstudio/learnr)
-->
