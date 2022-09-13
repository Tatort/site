---
title: Some of my publications
author: Travis M. Thomas
#raw: "https://raw.githubusercontent.com/rbind/blogdown-demo/master/content/post/2017-08-#28-adding-citations-to-posts.Rmd"
date: '2017-08-28'
slug: adding-citations-to-posts
bibliography: [/website/site/content/publications/Publications.bib]
link-citations: true
nocite: | 
  @R-bookdown
---

```{r setup, include = FALSE}
knitr::opts_chunk$set(comment = NA, eval = FALSE)

# load packages
packages <- c("bookdown", "blogdown", "knitr")
lapply(packages, function(x) {
  if (!requireNamespace(x)) install.packages(x)
  library(x, character.only = TRUE)
})
```





