# R-codes-Probability-Theory-and-Statistical-Inference
#Relative Frequency or Empirical Probability converges when experiment is repeated large number of times
######################################
n = 10
Coin10 = c()
Coin10 = sample( c(0,1), size = n, replace = T)
Coin10 
table(Coin10)/length(Coin10) #relative frequency

######################################
n = 100
Coin10 = c()
Coin10 = sample( c(0,1), size = n, replace = T)
Coin10 
table(Coin10)/length(Coin10) #relative frequency

######################################
n = 1000
Coin10 = c()
Coin10 = sample( c(0,1), size = n, replace = T)
Coin10 
table(Coin10)/length(Coin10) #relative frequency



