---
title: "Developing Data Products Week 2 Assignment"
author: "Pooi Mun"
date: "9/18/2019"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Developing Data Products
To create a web page using R Markdown that features a map created with Leaflet.

### 1. Loading library
```{r}
library(leaflet)
```

### 2. Create map 
```{r}
map <- leaflet() %>%
addTiles() %>%
addMarkers(lat=3.157167, lng=101.712306, popup = "Petronas Twin Towers") %>%
addMarkers(lat=3.152483, lng=101.703641, popup = "KL Tower")
map
```
