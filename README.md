---
title: "Queller-Phil-ADA-homework-1"
author: "Phil Queller"
date: "2/4/2020"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## homework 1

# challenge 1

```{r}

quote <- gsub("[[:punct:]]","","There is grandeur in this view of life, with its several powers, having been originally breathed by the Creator into a few forms or into one; and that, whilst this planet has gone circling on according to the fixed law of gravity, from so simple a beginning endless forms most beautiful and most wonderful have been, and are being evolved")

quote

split_quote <- str_split(quote, " ")[[1]]
split_quote

every_fourth <- split_quote[seq(from = 4, to = 60, by = 4)]
every_fourth

every_fourth <- sort(every_fourth, decreasing = TRUE)
every_fourth


```
# challenge 2
```{r}

```
