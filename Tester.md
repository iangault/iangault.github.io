Tester
================
2025-10-02

## R Markdown

This is equal to *4* will this be a new line? but this one won’t?<br/>
maybe because of br.

two enters works?

two enters and 2 spaces above

``` r
getwd()
```

    ## [1] "/Users/iangault/git/MDS/iangault.github.io"

``` r
here()
```

    ## [1] "/Users/iangault/git/MDS/iangault.github.io"

``` r
here("data", "fake_file.txt")
```

    ## [1] "/Users/iangault/git/MDS/iangault.github.io/data/fake_file.txt"

``` r
text <- readLines(here("data", "fake_file.txt"))
text
```

    ## [1] "Hello World"

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Tester_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
