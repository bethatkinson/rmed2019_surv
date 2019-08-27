Wrangling Survival Data: <br>From Time-dependent Covariates to
Multistate Endpoints
================

### [R/Medicine 2019 conference](https://r-medicine.com/)

-----

🗓 September 12, 2019  
🕗 01:00pm - 05:00pm  
📍 Boston, MA  
✅ [Register](https://cvent.me/en41V)

-----

## Overview

In this four-hour workshop, I will review basic code for standard
survival analysis, then work through examples for more complex
scenarios. The majority of the focus will be on creating the correct
dataset using tools available in the `survival` package. The final
portion of the class will explore the most complex scenario - multistate
data. The format will be a mix of lecture and hands-on exercises.

## Learning objectives

  - Understand different survival data formats
  - Create start/stop data using functions in the `survival` package
  - Check data for errors
  - Create multistate data and perform basic analysis

## Is this course for me?

This workshop is targeted at people who work in the medical field with
survival data (or who anticipate needing to work with it). A very basic
understanding of survival analysis will be helpful, though not required.
A basic understanding of R is assumed.

  - Have you had to manipulate data prior to running time-to-event
    analysis?
  - Do you anticipate needing to run analyses with time-dependent
    covariates or multiple endpoints?
      - *Even better,* have you used the `survival` package?
  - Have you used R with the RStudio Integrated Development Environment
    (IDE)? Are you familiar with the various “panes” and “tabs”? For
    instance, can you quickly find all objects in your current global
    environment, and can you send R code from a source file (.R, .Rmd)
    to the console?

## Schedule

| Time          | Activity                                |
| :------------ | :-------------------------------------- |
| 01:00 - 01:50 | Session 1 (basic analysis, motivation)  |
| 01:50 - 02:00 | *Break*                                 |
| 02:00 - 02:50 | Session 2 (intro to tools, examples)    |
| 02:50 - 03:00 | *Break*                                 |
| 03:00 - 03:50 | Session 3 (check data, common mistakes) |
| 03:50 - 04:00 | *Break*                                 |
| 04:00 - 04:50 | Session 4 (multistate data)             |
| 04:50 - 05:00 | Wrap-up / Overtime                      |

## Instructor

Beth Atkinson has been a statistician at Mayo Clinic for 29 years and
has worked with Splus then R since starting at Mayo, including
development work on the `rpart` package. She has worked extensively with
Terry Therneau, author of the `survival` package, and has spent many
hours wrangling data so that it is set up appropriately for
time-to-event analyses. Currently she is working with Terry and Cindy
Crowson on a book focused on time-to-event analyses, which will include
an on-line compendium of detailed examples.

## Pre-work

Welcome to the [Wrangling Survival
Data](https://github.com/bethatkinson/rmed2019_surv) workshop\! I look
forward to meeting you in person. Before attending the workshop, please
complete the following prework:

<br>

1.  Sign up for a free RStudio Cloud account at <https://rstudio.cloud/>
    before the workshop. I recommend logging in with an existing Google
    or GitHub account, if you have one (rather than creating a new
    account with another password you have to remember).

2.  Please bring a laptop that has the following installed:
    
      - A recent version of R (\>=3.6.0), which is available for free at
        <https://cloud.r-project.org/>
      - A recent version of RStudio Desktop (\>=1.2), available for free
        ([RStudio Desktop Open Source
        License](https://www.rstudio.com/products/rstudio/download/#download))
      - The R packages we will use, which you can install by connecting
        to the internet, opening RStudio, and running at the command
        line:
    
    <!-- end list -->
    
    ``` r
    install.packages(c("survival", "survminer", "tidyverse",
                       "lubridate", "arsenal", "broom"))
    ```

3.  Don’t forget your power cord\!

On the day of the workshop, I’ll provide you with an RStudio Cloud
project that contains all of the course materials. We will use the
software listed above only as an important backup should there be
problems with the on-site internet
connection.

-----

[![forthebadge](https://forthebadge.com/images/badges/cc-by.svg)](https://creativecommons.org/licenses/by/4.0/)  
This work is licensed under a [Creative Commons Attribution 4.0
International License](https://creativecommons.org/licenses/by/4.0/).
