library("GA")
library(ggplot2)

# creating dataset - simulating
df <- data.frame(id=seq(1,100),car=round(runif(100,1,5)),driver=round(runif(100,1,5)),
                 city=round(runif(100,5,20)),distance=round(runif(n = 100,min = 30,max = 50)))

GA <- ga(type = "real-valued", fitness = f, lower = c(th = lbound), upper = ubound)
summary(GA)
