# Josh22222
 
---
title: "Josh"
author: "Josh"
date: "5/6/2022"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
library(tidyverse)
library(lubridate)
library(janitor)
```

```{r}
complaints %>%
  filter(state == "NC") %>%
  group_by(product)
```
