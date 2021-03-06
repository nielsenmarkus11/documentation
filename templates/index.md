# Welcome to healthcareai

This package will get you started with healthcare machine learning in R.

## What can you do with it?

* Create and compare models based on your data.
* Save and deploy a model.
* Perform risk-adjusted comparisons.
* Do trend analysis following [Nelson rules](https://en.wikipedia.org/wiki/Nelson_rules).
* Improve sparse data via longitudinal imputation.

------------------

## How is it specific to healthcare?

* Longitudinal machine learning via mixed models
* Longitudinal imputation
* Risk-adjusted comparisons

------------------

## How to install

Work in the console of RStudio or RGui

* Grab prerequisites
```{r}
install.packages(c('caret','data.table','devtools','doParallel','e1071','grpreg','lme4','lubridate','pROC','R6','ranger','ROCR','RODBC'),repos = "https://cran.cnr.berkeley.edu/")
```

* Install healthcareai
```{r}
library(devtools)
devtools::install_github(repo='HealthCatalystSLC/healthcareai-r')
```

* Load the package and read the built-in docs
```{r}
library(healthcareai)
?healthcareai
```

------------------

## How to help

Check out our github [repo](https://github.com/HealthCatalystSLC/healthcareai-r/blob/master/README.md).