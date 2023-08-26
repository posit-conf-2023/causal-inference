
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Visit the main workshop repository

This repo is a snapshot in time of the workshop delivered at
`posit::conf(2023)`. [Visit the workshop’s main repo for the latest
version of the
material](https://github.com/malcolmbarrett/causal_inference_r_workshop).

## Causal Inference in R Workshop

------------------------------------------------------------------------

:spiral_calendar: September 17 and 18, 2023  
:alarm_clock: 09:00 - 17:00  
:hotel: ROOM TBD  
:writing_hand: [pos.it/conf](http://pos.it/conf)

------------------------------------------------------------------------

### Slides

- [00
  Intro](https://causal-inference-r-workshop.netlify.app/00-intro.html)
- [01 Whole
  Game](https://causal-inference-r-workshop.netlify.app/01-causal_modeling_whole_game.html)
- [02 When Standard Methods
  Succeed](https://causal-inference-r-workshop.netlify.app/02-when-standard-methods-succeed.html)
- [03 Causal Inference with `group_by` and
  `summarise`](https://causal-inference-r-workshop.netlify.app/03-causal-inference-with-group-by-and-summarise.html)
- [04 Causal
  Diagrams](https://causal-inference-r-workshop.netlify.app/04-dags.html)
- [05 Causal Inference is Not Just a Statistics
  Problem](https://causal-inference-r-workshop.netlify.app/05-quartets.html)
- [06 Introduction to Propensity
  Scores](https://causal-inference-r-workshop.netlify.app/06-pscores.html)
- [07 Using Propensity
  Scores](https://causal-inference-r-workshop.netlify.app/07-using-pscores.html)
- [08 Checking Propensity
  Scores](https://causal-inference-r-workshop.netlify.app/08-pscore-diagnostics.html)
- [09 Fitting the outcome
  model](https://causal-inference-r-workshop.netlify.app/09-outcome-model.html)
- [10 Continuous Exposures and
  G-Computation](https://causal-inference-r-workshop.netlify.app/10-continuous-g-comp.html)
- [11 Tipping Point Sensitivity
  Analyses](https://causal-inference-r-workshop.netlify.app/11-tipr.html)
- [12 Whole Game (Your
  Turn)](https://causal-inference-r-workshop.netlify.app/12-whole_game-2.html)
- [13 Bonus: Selection
  Bias](https://causal-inference-r-workshop.netlify.app/13-bonus-selection-bias.html)
- [14 Bonus: Continous Exposures with Propensity
  Scores](https://causal-inference-r-workshop.netlify.app/14-bonus-continuous-pscores.html)

### Installing materials locally

We will be using Posit Cloud for the workshop, but if you would like to
install the required packages and course materials, we have an R package
called
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)} to
help you do that! You can install
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)}
from GitHub with:

``` r
install.packages("remotes")
remotes::install_github("malcolmbarrett/causalworkshop")
```

Once you’ve installed the package, install the workshop with

``` r
causalworkshop::install_workshop()
```

By default, this package downloads the materials to a conspicuous place
like your Desktop. You can also tell `install_workshop()` exactly where
to put the materials:

``` r
causalworkshop::install_workshop("a/path/on/your/computer")
```

## Schedule

### Day 1

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |

### Day 2

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |
