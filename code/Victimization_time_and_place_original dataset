---
  title: "victimisation"
author: "Alshaun Godinet"
date: "22/08/2020"
output: pdf_document
---
  
  ```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


```{r}
library(dplyr)
library(tidyr)
library(zoo)
library(xts)
library(lubridate)
library(timetk)
library(tsibble)
library(tidyverse)
library(stringr)
```


```{r}
df <- read.csv(file="victimisation_time and place_original.csv", header = TRUE)
str(df)

```


```{r}
Victimization_time_and_place <- subset(df, select=c("Month.Year","ANZSOC.Group","Area.Unit","Meshblock","Territorial.Authority"))

```