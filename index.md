---
title       : Shiny App Description 
subtitle    : qqnorm samples
author      : cdurso17
job         : CSV
framework   : io2012  # {io2012, html5slides, shower, deck.js,dzslides, landslide, Slidy...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax,quiz,bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The QQ plot 

Plotting the quantiles of a sample distribution against quantiles for the standard normal distribution gives a visual for the normality of the sample. Generally, the better the points line up with the qq-line, the more normal the distribution.

--- .class #id 

## Example

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

---

## Motivation

Interpretation can be difficult. perfectly normal but moderate-sized samples may not trace out the qq-line perfectly, as seen below.

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

---

## Heavy Tails

A points from a distribution with heavy tails will follow a curve that starts below the qq-line on the left and ends above the qq-line on the right.
![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

--- 

### Large Normal Sample

Points from a large, normal sample will lie close to the qq-line except near the ends.

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 









