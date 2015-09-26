---
title       : Publishing Slidify for Data Products
subtitle    : Take 1
author      : Victor Mo
job         : Data Course
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

Statistics
R random sampling.

1. Sample mean = x = ( ?? xi ) / n
2. Sample standard deviation = s = sqrt [ ?? ( xi - x )2 / ( n - 1 ) ]
3. Sample variance = s2 = ?? ( xi - x )2 / ( n - 1 )
4. Variance of sample proportion = sp2 = pq / (n - 1)
5. Pooled sample proportion = p = (p1 * n1 + p2 * n2) / (n1 + n2)

**Chao

-----

## Slide 2

Correlation
1. Pearson product-moment correlation = r = ?? (xy) / sqrt [ ( ?? x2 ) * ( ?? y2 ) ]
2. Linear correlation (sample data) = r = [ 1 / (n - 1) ] * ?? { [ (xi - x) / sx ] * [ (yi - y) / sy ] }
3. Linear correlation (population data) = ?? = [ 1 / N ] * ?? { [ (Xi - ??X) / ??x ] * [ (Yi - ??Y) / ??y ] }

----

## Slide 3

1. Simple Linear Regression
2. Simple linear regression line: y = b0 + b1x
3. Regression coefficient = b1 = ?? [ (xi - x) (yi - y) ] / ?? [ (xi - x)2]
4. Regression slope intercept = b0 = y - b1 * x
5. Regression coefficient = b1 = r * (sy / sx)
6. Standard error of regression slope = sb1 = sqrt [ ??(yi - yi)2 / (n - 2) ] / sqrt [ ??(xi - x)2 ]

