# Data 624: Project 2

**Team Members**: Ali Ahmed, Andreina Arias, Kaylie Evans, Naomi Buell, and Zaneta Paulusova

## Overview

This project addresses new regulatory requirements for ABC Beverage Company by analyzing the manufacturing process and identifying predictive factors influencing the **pH level** of products. Our data science team was tasked with building a predictive model for pH and presenting both technical and non-technical findings.

## Project Contents

-   `Non-Technical Report.pdf`: Non-technical report
-   `Technical_Report.Qmd`: Technical report, including code and documentation
-   `TechnicalReport.pdf`: PDF render of technical report, including code output
-   `PH_forecasts.xlsx`: Final predictions for the pH values of the evaluation dataset

## Libraries Used

``` r
library(DataExplorer)
library(tidyverse)
library(readxl)
library(fpp3)
library(caret)
library(skimr)
library(doParallel)
library(RWeka)
library(rpart)
library(corrplot)
library(openxlsx)
library(tidyr)
library(mice)
library(janitor)
library(dplyr)
```
