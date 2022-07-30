sales<-read.csv("SALES.csv")
sales
fit<-lm(sales$cnt~sales$temp+sales$atemp+sales$hum+sales$windspeed,data=sales)
fit
summary(fit)
