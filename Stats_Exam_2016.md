Stats Exam 2016
================
Carmen Roberts
2016/08/30

Question 1
----------

**Null Hypothesis:** There is no difference in oral body temperature and heart rate between males and females.

**Alternative Hypothesis:** There is a difference in oral body temperature and heart rate between males and females.

**Statistical test(s):** Body temperature and heart rate are normally distributed, parametric, paired data and is on an interval scale.Therefore a one-way repeated-measures ANOVA will be used to test the hypothesis. Significance set at p&lt;0.05

**Assumptions:** Equal variance across groups. The errors are independent. Data is matching effective.

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

    ## Parsed with column specification:
    ## cols(
    ##   body_temperature = col_double(),
    ##   male = col_integer(),
    ##   female = col_integer()
    ## )

    ##  body_temperature      male           female     
    ##  Min.   :35.70    Min.   :58.00   Min.   :57.00  
    ##  1st Qu.:36.60    1st Qu.:70.00   1st Qu.:68.00  
    ##  Median :36.80    Median :73.00   Median :76.00  
    ##  Mean   :36.81    Mean   :73.37   Mean   :74.15  
    ##  3rd Qu.:37.10    3rd Qu.:78.00   3rd Qu.:80.00  
    ##  Max.   :38.20    Max.   :86.00   Max.   :89.00  
    ##                   NA's   :65      NA's   :65
