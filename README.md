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

### Lab 1 

Install the following packages before running the tutorial.


```
install.packages(c("remotes","learnr","ggplot2","PerformanceAnalytics","lattice","summarytools","Hmisc","table1","psych"))
```

Exploratory Data Analysis with base R command.

### Lab 2 

Install the following packages before running the tutorial.


```
install.packages(c("ggplot2","gridExtra","ggforce","statsExpressions","ggalt","bbplot","leaflet","ggcorplot","izmir","mlbench"))
```

+ Fundamentals of the ggplot2

+ Exploratory Data Analysis using ggplot2.

+ Creating an interactive map with leaflet. 

### Lab 3 

Install the following packages before running the tutorial.


```
install.packages(c("dplyr","stringr","editrules","deducorrect","lubridate","assertive","gapminder"))
```
+ Data Cleaning 

+ Text and Categorical Data Cleaning with `stringr`

+ Example for `editrules`


### Lab 4 

Install the following packages before running the tutorial.

```
install.packages(c("ISLR","dplyr","corrplot","PerformanceAnalytics","glmnet","GGally","car"))
```

+ Lasso Regression 

+ Ridge Regression 

+ Elastic Net 

### Lab 5 

Install the following packages before running the tutorial.

```
install.packages(c("interaction"))
```

+ Confounding

+ Interaction

### Lab 6 

Install the following packages before running the tutorial.

```
install.packages(c("simputation","missForest","Hmisc","mice","VIM","tidyr","lavaan",
"naniar","datasets","rcompanion","bestNormalize","MASS","gridExtra"))
```

+ Transformation 

+ Handling with missing data in R

### Lab 7

Install the following packages before running the tutorial.

```
install.packages(c("caret","dplyr","tidyr","datasets","factoextra","pls"))
```

+ Model Complexity and Overfitting

+ Dimension Reduction

### Lab 8

Install the following packages before running the tutorial.

```
install.packages(c("vcd","ggmosaic","ltm","polycor","ISLR","caret","corrplot","MASS"))
devools::install_version("InformationValue", version = "1.2.3", repos = "http://cran.us.r-project.org")
devtools::install_version("DMwR", version = "0.4.1", repos = "http://cran.us.r-project.org"
```
+ Categorical Data Analysis
+ Logistic Regression 
+ Robust Regression

### Lab 9

```
install.packages(c("Boruta","plspm")) 
devtools::install_version("gradDescent", version = "3.0", repos = "http://cran.us.r-project.org")
```
+ Supervised Learning
  + Gradient Descent Algorithm
+ Boruta Feature Selection
+ One-Hot Encoding

### Lab 10

```
install.packages(c("tidyverse","neuralnet","GGally","nnet","caret"))
```
+ Artificial Neural Network 

### Lab 11

```
install.packages(c("e1071" , "caret" ,"datarium" ,"GGally","mlbench" ,"caret","dplyr", "kernlab"))
```

+ Support Vector Machines 

### Lab 12
```
install.packages(c("randomForest" , "caret" ,"xgboost" ,"GGally","mlbench" ,"caret","dplyr", "e1071","gbm","iml","naivebayes"))
```
+ Naive Bayes Algorithm 
+ Decision Tree
+ Random Forest
+ Boosting
  + Gradient Boosting
  + XGBoost (Extreme Gradient Boosting)
+ Explainable AI Components; Variable Imporance Plot & Shapley Value

