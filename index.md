---
title       : A Shiny App of Steps Calculator
subtitle    : 
author      : 
job         : 
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What does it look like? 

<iframe src = 'http://amyherml.shinyapps.io/creatingDataProduct/' height='600px'></iframe>

--- .Screen #id 

## Functions

Click to visit Shiny App: 
https://amyherml.shinyapps.io/creatingDataProduct/

This shiny app will help user to calculate the BMI and give a recommended daily steps based on the user's aim. 

This Shiny app have the following functions: 

1. Calculate the body mass index(BMI)
2. Compare the BMI calculated with the NHS defined healthy weight regions
3. Calculate the recommended steps per day based on the user's aim

--- .Functions #id 


## BMI
$$BMI = \frac{Weight_{kg}}{Hight_{m}^2}$$
Example in R: 

```r
Weight <- 55  #in kg  
Height <- 1.65  #in meters
BMI <- Weight/Height^2 # in kg/meters^2
print(BMI)
```

```
## [1] 20.20202
```

For more details,visit: 
- http://en.wikipedia.org/wiki/Body_mass_index
- http://www.nhs.uk/Tools/Pages/Healthyweightcalculator.aspx

--- .BMI #id 

## Steps
It is recommended to walk 8000 steps per day to maintain a health life. Depending on the personal aim. 

- 10000 steps if trying to loss weight
- 8000 steps if trying to maintain weight
- 6000 steps if trying to gain weight 

### Thank you!

--- .Steps #id

