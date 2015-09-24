---
title       : Pitch Miles Per Gallon Predictor
subtitle    : Why data science matters for the environment!
author      : Oliver Carr
job         : Software Craftsman
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, interactive]
url: {lib: ./libraries}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : ozoli-avatar.png
biglogo     : ozoli-avatar.png
assets      : {assets: ./}
--- .class #id

# How important is fuel consumption?

- Volkswagen understand! Fuel costs are a cost on the environment
- Depending on your country the higher fuel consumption of your car the higher tax you will pay
- Fuel costs also influence a person's budget

--- .class #id

## Measuring Fuel Consumption

- To measure fuel consumption a Miles per Gallon (mpg) is used in USA, Canada and the UK
- We will use US gallons which is 3.785 liters.

--- .class #id

## Our Solution

- Let people calculate the fuel economy of the car they would like to buy
- Using historical data, so real data! Not a formula like 2 + 3 = 

```
## [1] 5
```
- Modeled with a good accuracy for unseen car types.
- Try it out now: https://ozoli.shinyapps.io/repo
