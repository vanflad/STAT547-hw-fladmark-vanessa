#  Homework 8

## Building a Shiny App!

### November 21st, 2017


Relevant Links:

* The [homework instructions](http://stat545.com/hw08_shiny.html)

* Behold! The [Shiny app](https://vanflad.shinyapps.io/Juvenile_Salmon_Sampling/) in all it's glory!

* The [folder](https://github.com/vanflad/STAT547-hw-fladmark-vanessa/tree/master/Homework%208/Shiny) with all the code where [ui.R](https://github.com/vanflad/STAT547-hw-fladmark-vanessa/blob/master/Homework%208/Shiny/ui.R), [server.R](https://github.com/vanflad/STAT547-hw-fladmark-vanessa/blob/master/Homework%208/Shiny/server.R) and [app.R](https://github.com/vanflad/STAT547-hw-fladmark-vanessa/blob/master/Homework%208/Shiny/app.R) reside

* The [raw data](https://github.com/vanflad/STAT547-hw-fladmark-vanessa/tree/master/Homework%208/data) from Hakai's sampling program if you feel so inclined to take a look!

Need to explain what the data is all about here too... blah blah I need to pick out some fishies! *****

Trouble-shooting Links:

* Cheetsheet on [Shiny](http://shiny.rstudio.com/images/shiny-cheatsheet.pdf) from R Studio

* Solving the error message when first attempting to [publish](https://support.rstudio.com/hc/en-us/articles/220339568-What-does-Disconnected-from-Server-mean-in-shinyapps-io-) onto shiny.io

* How to properly use `if(){}else{}` [functions](http://www.dummies.com/programming/r/how-to-chain-ifelse-statements-in-r/) for `conditionalPanel()` coding use

* Why isn't my [`dataTableOutput` rendering](https://github.com/rstudio/DT/issues/140) when published?! Oh, it's because the `DT` library needs to be included in both server and ui, either using `library(DT)` or `DT::dataTableOutput`, as another Github user discovered for me!

* I'm sure there will be more to add here later when I make things more nice and fancy!