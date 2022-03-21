README
================
Monica Impaglia
2022-03-21

``` r
args(read.csv)  
```

    ## function (file, header = TRUE, sep = ",", quote = "\"", dec = ".", 
    ##     fill = TRUE, comment.char = "", ...) 
    ## NULL

``` r
read.csv(file = "C:\\Users\\Home\\OneDrive\\Desktop\\pa_2\\data\\data.csv") 
```

    ##       info durationV     f0   int
    ## 1   capo_1      0.13 170.80 68.28
    ## 2   capo_2      0.09 164.92 65.80
    ## 3  pinto_1      0.17 203.88 65.31
    ## 4  pinto_2      0.12 184.98 64.34
    ## 5   pujo_1      0.14 195.58 70.59
    ## 6   pujo_2      0.09 192.03 68.94
    ## 7  quemo_1      0.11 175.05 69.82
    ## 8  quemo_2      0.07 173.04 68.57
    ## 9  testo_1      0.09 177.08 67.24
    ## 10 testo_2      0.08 169.58 64.56

``` r
my_data <- read.csv("C:\\Users\\Home\\OneDrive\\Desktop\\pa_2\\data\\data.csv")  
```

``` r
mean(my_data$durationV)
```

    ## [1] 0.109

``` r
mean(my_data$f0)
```

    ## [1] 180.694

``` r
mean(my_data$int)
```

    ## [1] 67.345
