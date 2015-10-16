# kittykatz
install.packages("devtools")
library(devtools)
devtools::install_github("hilaryparker/cats")
library(ggplot2)
library(cats)


ggplot(mpg, aes(cty, hwy)) +
 add_cat() +
 geom_point()
