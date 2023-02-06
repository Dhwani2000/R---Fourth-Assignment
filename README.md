# R---Fourth-Assignment

> Frequency <-c (0.6,0.3,0.4,0.4,0.2,0.6,0.3,0.4,0.9,0.2)
> BP <-c (103,87,32,42,59,109,78,205,135,176)
> First <-c (1,1,1,1,0,0,0,0,NA,1)
> Second <-c (0,0,1,1,0,0,1,1,1,1)
> FinalDecision <-c (0,1,0,1,0,1,0,1,1,1)

> hospital.df <- data.frame(Frequency, BP, First, Second, FinalDecision)
> hospital.df
   Frequency  BP First Second FinalDecision
1        0.6 103     1      0             0
2        0.3  87     1      0             1
3        0.4  32     1      1             0
4        0.4  42     1      1             1
5        0.2  59     0      0             0
6        0.6 109     0      0             1
7        0.3  78     0      1             0
8        0.4 205     0      1             1
9        0.9 135    NA      1             1
10       0.2 176     1      1             1

> boxplot(BP, main = "Observation of Patient's BP", col = "brown")

> hist(BP, main = "Observation of Patient's BP", col = "pink")

> mean(FinalDecision)
[1] 0.6
