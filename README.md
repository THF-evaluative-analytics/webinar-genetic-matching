# Genetic matching using R

Here you can find all resources for the IAU workshop on running genetic matching in R. This workshop aims to teach the basic principles of how to run genetic matching using observational data, where we would like to examine the change made by an intervention to a healthcare outcome. In this workshop we also run some introductory data checks and produce descriptive statistics to understand the structure of a fake healthcare dataset provided.


Link to [slides](https://thf-evaluative-analytics.github.io/webinar-genetic-matching/gen-match-slides.html#1)


## Data source

This project does not use any real data. We built a small fake dataset intended to replicate a patient level data where some patients received an intervention aimed at reducing a negative outcome.

## How does it work?

To code along in the workshop you need to download this repo. You can do this either by cloning it or downloading a zip folder by clicking the green code button. You also need to have the following packages installed and recently updated (in the last year). 

* [**tidyverse**](https://www.tidyverse.org/)
* [**tidylog**](https://cran.r-project.org/web/packages/tidylog/index.html)
* [**gtsummary**](https://cran.r-project.org/web/packages/gtsummary.html)
* [**skimr**](https://cran.r-project.org/web/packages/skimr/index.html) 
* [**broom**](https://cran.r-project.org/web/packages/broom/index.html)
* [**Matching**](https://cran.r-project.org/web/packages/Matching/index.html)
* [**rgenoud**](https://cran.r-project.org/web/packages/rgenoud/index.html)
* [**here**](https://cran.r-project.org/web/packages/here/index.html)

### Getting started

The 'R' folder contains:

1. 1_Create fake data for workshop.R
* generates and saves the fake data as well as runs the matching and saves the output. You can run this script but all the outputs are already available in the data folder. Please note that running this script is likely to be very CPU intensive.

2. workshop_for_participants.Rmd
* Instructions and exercises for participants.
3. workshop_with_answers.Rmd
* Same as 2 but with possible solutions to the exercises. 


## Data source

This project does not use any real data. We built a small fake dataset intended to replicate a patient level data where some patients received an intervention aimed at reducing a negative outcome

## Authors

This workshop was created and delivered by 

* Emma Vestesson  [Github](www.github.com/emma) / [Twitter](www.twitter.com/gummifot)
* Paris Pariza  [GitHub](https://github.com/Ppariz) / [Twitter](https://twitter.com/ParizaParis)
* Richard Brine 
