# Statistical Data Analysis (STAT 412), Department of Statistics, METU, Spring 2023

This repository involves the tutorials about the statistical data analysis. You can install this package and run the interactive tutorials on your R console easily. 

To install the package to your R enviroment.

```
remotes::install_github("ozancanozdemir/statisticaldataanalysis")
```
Then, run the following command to open the interactive tutorial page.  For example, 



```
library(statisticaldataanalysis)
learnr::run_tutorial("Recitation1",package = "statisticaldataanalysis")
```

### Recitation 1 

Install the following packages before running the tutorial.


```
install.packages(c("remotes","learnr","ggplot2","PerformanceAnalytics","lattice","summarytools","Hmisc","table1","psych"))
```

Exploratory Data Analysis with base R command.

### Recitation 2 

Install the following packages before running the tutorial.


```
install.packages(c("ggplot2","gridExtra","ggforce","statsExpressions","ggalt","bbplot","leaflet","ggcorplot","izmir","mlbench"))
```
+ Fundamentals of the ggplot2

+ Exploratory Data Analysis using ggplot2.

+ Creating an interactive map with leaflet. 

### Recitation 3 

Install the following packages before running the tutorial.


```
install.packages(c("dplyr","stringr","editrules","deducorrect","lubridate","assertive","gapminder"))
```
+ Data Cleaning 

+ Text and Categorical Data Cleaning with `stringr`

+ Example for `editrules`
