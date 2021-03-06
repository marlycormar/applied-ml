# Applied Machine Learning

### rstudio::conf 2020

-----

:spiral\_calendar: January 27 and 28, 2020<br/>
:alarm\_clock: 09:00 - 17:00<br/>
:hotel: Continental Ballroom Rooms 4 (Ballroom Level)<br/>
:writing\_hand: [rstd.io/conf](http://rstd.io/conf)<br/>
:ledger: Part [1](https://rstudio-conf-2020.github.io/applied-ml/Part_1.html) [2](https://rstudio-conf-2020.github.io/applied-ml/Part_2.html) [3](https://rstudio-conf-2020.github.io/applied-ml/Part_3.html) [4](https://rstudio-conf-2020.github.io/applied-ml/Part_4.html) [5](https://rstudio-conf-2020.github.io/applied-ml/Part_5.html) [6](https://rstudio-conf-2020.github.io/applied-ml/Part_6.html)

-----

<img src="https://github.com/rstudio-conf-2020/applied-ml/raw/master/images/rotate.gif" width="400" align="middle" class="center">

-----

## Overview

Machine learning is the study and application of algorithms that learn from and make predictions on data. From search results to self-driving cars, it has manifested itself in all areas of our lives and is one of the most exciting and fast-growing fields of research in the world of data science.

This two-day course will provide an overview of using R for supervised learning. The session will step through the process of building, visualizing, testing, and comparing models that are focused on prediction.

The goal of the course is to provide a thorough workflow in R that can be used with many different regression or classification techniques. Case studies on real data will be used to illustrate the functionality and several different predictive models are illustrated. The course focuses on both low- and high-level approaches to modeling using the tidyverse and uses several types of models for illustration.

## Learning objectives

Attendees will be able to use the tidymodels packages to create, tune, fit, visualize, and assess models created for the purpose of prediction.

## Is this course for me?

This course requires basic familiarity with R and the tidyverse.

## Prework

If you want to read up a bit about predictive modeling before the workshop, check out [chapter 1](https://bookdown.org/max/FES/intro-intro.html) and [chapter 3](https://bookdown.org/max/FES/review-predictive-modeling-process.html) of [*Feature Engineering and Selection*](https://bookdown.org/max/FES/).

We will have RStudio server pro instances with all of the packages installed as well as the above GitHub repository available.

If you would like to run R locally, the installation instructions are:

``` r
install.packages(
  c(
    'AmesHousing',
    'C50',
    'devtools',
    'discrim',
    'earth',
    'ggthemes',
    'glmnet',   # See important note below
    'klaR',
    'lubridate',
    'modeldata',
    'party',
    'pROC',
    'rpart',
    'stringr',
    'textfeatures',
    'tidymodels'
  ),
  repos = "http://cran.rstudio.com"
)
devtools::install_github(c(
  "tidymodels/tidymodels",
  "tidymodels/tune",
  "tidymodels/textrecipes",
  "koalaverse/vip",
  "gadenbuie/countdown"
))
```

**Important note\!** A new version of `glmnet` was released on 2019-11-09. Although it states that it depends on R (≥ 3.5.0), it may not install on R versions \< 3.6.0.

We will be on-site at least 30min before the workshop commences in case you need any help getting packages installed. Prior to this, you can email `max@rstudio.com` with questions.

## Note

We don’t provide the `Rmd` files for the slides mostly because they are complex and we don’t support them. However, we do get requests for people who would like to use them as a template so we provide `Part_1.Rmd` if you want to use this format for your presentations.

## Schedule

| Time          | Activity       |
| :------------ | :------------- |
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |

## Instructors

Max Kuhn and Davis Vaughan

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
