# Genetic matching using R

Here you can find all resources for the IAU workshop on running genetic matching in R. This workshop aims to teach the basic principles of how to run genetic matching using observational data, where we would like to examine the change made by an intervention to a healthcare outcome. In this workshop we also run some introductory data checks and produce descriptive statistics to understand the structure of a fake healthcare dataset provided.

Link to [slides](https://thf-evaluative-analytics.github.io/webinar-genetic-matching/gen-match-slides.html#1)

## Workshop instructions

To code along in the workshop you need to download this repo. You can do this either by cloning it or downloading a zip folder by clicking the green code button. You also need to have the following packages installed and recently updated (in the last year).

-   [**tidyverse**](https://www.tidyverse.org/)
-   [**tidylog**](https://cran.r-project.org/web/packages/tidylog/index.html)
-   [**gtsummary**](https://cran.r-project.org/web/packages/gtsummary.html)
-   [**skimr**](https://cran.r-project.org/web/packages/skimr/index.html)
-   [**broom**](https://cran.r-project.org/web/packages/broom/index.html)
-   [**Matching**](https://cran.r-project.org/web/packages/Matching/index.html)
-   [**rgenoud**](https://cran.r-project.org/web/packages/rgenoud/index.html)
-   [**here**](https://cran.r-project.org/web/packages/here/index.html)

### Getting started

The 'R' folder contains:

1.  1\_Create fake data for workshop.R

-   generates and saves the fake data as well as runs the matching and saves the output. You can run this script but all the outputs are already available in the data folder. Please note that running this script is likely to be very CPU intensive.

2.  workshop\_for\_participants.Rmd

-   Instructions and exercises for participants.

3.  workshop\_with\_answers.Rmd

-   Same as 2 but with possible solutions to the exercises.

## Data source

This project does not use any real data. We built a small fake dataset intended to replicate a patient level data where some patients received an intervention aimed at reducing a negative outcome

## Authors

This workshop was created and delivered by

-   Emma Vestesson [Github](www.github.com/emma) / [Twitter](www.twitter.com/gummifot)
-   Paris Pariza [GitHub](https://github.com/Ppariz) / [Twitter](https://twitter.com/ParizaParis)
-   Richard Brine

## Where to learn more

If you want to learn more

Stuart E. A. (2010). Matching methods for causal inference: A review and a look forward. *Statistical science : a review journal of the Institute of Mathematical Statistics*, *25*(1), 1--21. <https://doi.org/10.1214/09-STS313>

Diamond A, Sekhon JS. Genetic matching for estimating causal effects: a general multivariate matching method for achieving balance in observational studies. *Rev. Econ. Stat*. 2013;95(3):932–945. [doi: 10.1162/REST_a_00318](http://sekhon.berkeley.edu/papers/GenMatch.pdf)
