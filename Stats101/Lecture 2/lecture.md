---
title: "Lecture 2"
author: "Manuel"
date: "04/12/2015"
output: pdf_document
---

```{r}
setwd("~/Semester/Teaching/Stats101/Lecture 2")
```

We'll work with our own earthquake data, from earthquake.usgs.gov. I downloaded a Comma-Separated Value table with all the earthquakes for March 2015.

# Preparation

Let's read the file:
```{r}
earthquakes=read.csv("earthquakes.csv", header=TRUE)
summary(earthquakes)
```

# Graphs
## Histograms


## Stem and Leaf


## Dotplots


## Boxplots


# Shapes
## Modes
- Uniform
- Unimodal
- Bimodal
- Multimodal

# Numerical Description

## Median

## Spread
- For any data:
  - Range
  - IQR
  - 5 Numbers
- For symmetrical data
  - Mean
  - Standard Deviation
  