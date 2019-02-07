# AB2019
AB2019-Ordu- R ile İleri Veri Önişleme


## paketler:

rm(list=ls())
.packages = c("RXKCD","beepr","fortunes","Rcmdr", "fun", "plotly",
"magrittr", "networkD3", "dygraphs", "stringr", "rebus", "pryr",
"car","doBy","lubridate","VIM","mice", "Amelia","plyr","sqldf",
"dplyr", "Hmisc","pastecs","psych", "doBy", "reshape", "dbplyr",
"tables","janitor","epiDisplay","summarytools","gmodels","questionr",
"corrplot","PerformanceAnalytics","corrgram","plotrix","gclus",
"polycor","psych", "ggplot2","gdata","foreign","XLConnect","WriteXLS",
"rjson","readr","readxl","haven","xml2","rvest","jsonlite","DBI", 
"tidyverse", "hflights", "gapminder", "dplyr", "data.table", "Cairo",
"rversions","readr","anytime", "reshape2", "stringr","babynames",
"rebus", "stringi","glue","validate", "assertr","validatetools",
"errorlocate","devtools", "cat", "e1071", "hot.deck","HotDeckImputation",
"imputeTS", "mi", "mice", "missForest","MissMech","mtsdi","norm",
"VIMGUI", "rattle","yaImpute","Zelig", "pan", "naniar", 
"MissingDataGUI", "htmlwidgets","rpivotTable","sjPlot",
"sjmisc","huxtable", "outliers", "OutliersO3", "discretization", "GGally",
"ggExtra", "ggridges", "MASS", "purrr", "ggpubr",
"errorlocate", "funModeling","addinslist","anytime","DataLoader",
"writexl","dataPreparation","DataExplorer","dataCompareR","DataCombine",
"DataClean","datacheck","dlookr","DT","dtplyr","editData","ggeffects",
"dcmodify", "deductive", "plot3D", "readr","rlist","visdat","DescToolsAddIns",
"lintools", "lumberjack","ggplotAssist", "tcltk2","rgl","colourpicker",
"ggExtra", "ggThemeAssist", "shiny", "markdown","bigmemory")

.inst <- .packages %in% installed.packages()

if(length(.packages[!.inst]) > 0) install.packages(.packages[!.inst])

lapply(.packages, require, character.only=TRUE)


source("https://bioconductor.org/biocLite.R")
biocLite("impute")
