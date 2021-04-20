
# HumanKapital

HumanKapital enthält Unterichtsmaterial für den TU Kurs im Sommersemester 2021.

## Installation

Die Installation aus GitHub erfolgt via devtools. HumanKapital benötigt außerdem das Paket learnr und in Windows rtools (https://cran.r-project.org/bin/windows/Rtools/).

``` r
install.packages("devtools")
install.packages("learnr")

devtools::install_github("lkuld/HumanKapital")
```

## Beispiele


``` r
library(HumanKapital)
library(learnr)

## um die verfuegbaren Tutorien zu sehen
available_tutorials("HumanKapital")

## um ein Tutorium "Beispiel" zu beginnen
run_tutorials("Tutorial_1_Grundlagen", "HumanKapital")
```

