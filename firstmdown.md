---
title: "Untitled"
author: "Me"
date: "5/18/2020"
output: 
  html_document: 
    keep_md: yes
---





```r
a <- 2
b <- -3
x <- runif(40)
sig_sq <- 0.5
y <- a + b * x + rnorm(40,sd = sqrt(sig_sq))
plot(x,y)
abline(a,b)
```

![](firstmdown_files/figure-html/unnamed-chunk-1-1.png)<!-- -->
