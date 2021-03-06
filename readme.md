
ipify [![Travis-CI Build Status](https://travis-ci.org/gregce/ipify.svg?branch=master)](https://travis-ci.org/gregce/ipify) [![Coverage Status](https://coveralls.io/repos/github/gregce/ipify/badge.svg?branch=master)](https://coveralls.io/github/gregce/ipify?branch=master)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

> Get your public IP

Using the [`ipify` API](https://www.ipify.org) by [Rdegges](https://github.com/rdegges)

Installation and Documentation
------------------------------

`ipify` is available through both CRAN and GitHub:

To install the CRAN version:

``` r
install.packages("ipify")
```

To install the latest development version from GitHub:

``` r
install.packages("devtools")
devtools::install_github("gregce/ipify")
```

Usage
-----

You can see the package in action at <http://gregce.github.io/ipify/>

``` r
library(ipify)
get_ip()
get_ip(format="json")
get_ip(format="jsonp")
```

    ## [1] "73.162.222.85"
    ## $ip
    ## [1] "73.162.222.85"
    ## 
    ## [1] "callback({\"ip\":\"73.162.222.85\"});"

License
-------

[MIT](https://opensource.org/licenses/MIT) @ [Greg Ceccarelli](https://www.linkedin.com/in/gregceccarelli)
