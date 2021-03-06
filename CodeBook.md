---
title: "CodeBook"
output: html_document
keep_md: yes
---



## averageDataSet
Independent tidy data set with the average of each variable for each activity and each subject from averageDataSet.txt

```
## 'data.frame':	180 obs. of  68 variables:
##  $ activity                   : chr  "LAYING" "LAYING" "LAYING" "LAYING" ...
##  $ subject                    : int  1 2 3 4 5 6 7 8 9 10 ...
##  $ tBodyAcc.mean...X          : num  0.222 0.281 0.276 0.264 0.278 ...
##  $ tBodyAcc.mean...Y          : num  -0.0405 -0.0182 -0.019 -0.015 -0.0183 ...
##  $ tBodyAcc.mean...Z          : num  -0.113 -0.107 -0.101 -0.111 -0.108 ...
##  $ tBodyAcc.std...X           : num  -0.928 -0.974 -0.983 -0.954 -0.966 ...
##  $ tBodyAcc.std...Y           : num  -0.837 -0.98 -0.962 -0.942 -0.969 ...
##  $ tBodyAcc.std...Z           : num  -0.826 -0.984 -0.964 -0.963 -0.969 ...
##  $ tGravityAcc.mean...X       : num  -0.249 -0.51 -0.242 -0.421 -0.483 ...
##  $ tGravityAcc.mean...Y       : num  0.706 0.753 0.837 0.915 0.955 ...
##   [list output truncated]
```

## Codebook of variables of averageDataSet


```
## 
##  
##  
## activity 	 : 	  
## A character vector 
## 
##  ================== 
## subject 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  15.5   15.5    8.68   1      30    
## 
##  ================== 
## tBodyAcc.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.274  0.277   0.01   0.222  0.301 
## 
##  ================== 
## tBodyAcc.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.018 -0.017  0.01   -0.041 -0.001
## 
##  ================== 
## tBodyAcc.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.109 -0.108  0.01   -0.153 -0.075
## 
##  ================== 
## tBodyAcc.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.558 -0.753  0.45   -0.996 0.627 
## 
##  ================== 
## tBodyAcc.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.46  -0.509  0.5    -0.99  0.617 
## 
##  ================== 
## tBodyAcc.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.576 -0.652  0.4    -0.988 0.609 
## 
##  ================== 
## tGravityAcc.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.697  0.921   0.49   -0.68  0.975 
## 
##  ================== 
## tGravityAcc.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.016 -0.128  0.35   -0.48  0.957 
## 
##  ================== 
## tGravityAcc.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.074  0.024   0.29   -0.495 0.958 
## 
##  ================== 
## tGravityAcc.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.964 -0.969  0.03   -0.997 -0.83 
## 
##  ================== 
## tGravityAcc.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.952 -0.959  0.03   -0.994 -0.644
## 
##  ================== 
## tGravityAcc.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.936 -0.945  0.04   -0.991 -0.61 
## 
##  ================== 
## tBodyAccJerk.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.079  0.076   0.01   0.043  0.13  
## 
##  ================== 
## tBodyAccJerk.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.008  0.009   0.01   -0.039 0.057 
## 
##  ================== 
## tBodyAccJerk.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.005 -0.004  0.01   -0.067 0.038 
## 
##  ================== 
## tBodyAccJerk.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.595 -0.81   0.42   -0.995 0.544 
## 
##  ================== 
## tBodyAccJerk.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.565 -0.776  0.43   -0.99  0.355 
## 
##  ================== 
## tBodyAccJerk.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.736 -0.884  0.28   -0.993 0.031 
## 
##  ================== 
## tBodyGyro.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.032 -0.029  0.05   -0.206 0.193 
## 
##  ================== 
## tBodyGyro.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.074 -0.073  0.04   -0.204 0.027 
## 
##  ================== 
## tBodyGyro.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  0.087  0.085   0.04   -0.072 0.179 
## 
##  ================== 
## tBodyGyro.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.692 -0.789  0.29   -0.994 0.268 
## 
##  ================== 
## tBodyGyro.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.653 -0.802  0.35   -0.994 0.477 
## 
##  ================== 
## tBodyGyro.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.616 -0.801  0.37   -0.986 0.565 
## 
##  ================== 
## tBodyGyroJerk.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.096 -0.099  0.02   -0.157 -0.022
## 
##  ================== 
## tBodyGyroJerk.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.043 -0.041  0.01   -0.077 -0.013
## 
##  ================== 
## tBodyGyroJerk.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.055 -0.053  0.01   -0.092 -0.007
## 
##  ================== 
## tBodyGyroJerk.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.704 -0.84   0.3    -0.997 0.179 
## 
##  ================== 
## tBodyGyroJerk.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.764 -0.894  0.27   -0.997 0.296 
## 
##  ================== 
## tBodyGyroJerk.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.71  -0.861  0.3    -0.995 0.193 
## 
##  ================== 
## tBodyAccMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.497 -0.483  0.47   -0.986 0.645 
## 
##  ================== 
## tBodyAccMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.544 -0.607  0.43   -0.986 0.428 
## 
##  ================== 
## tGravityAccMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.497 -0.483  0.47   -0.986 0.645 
## 
##  ================== 
## tGravityAccMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.544 -0.607  0.43   -0.986 0.428 
## 
##  ================== 
## tBodyAccJerkMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.608 -0.817  0.4    -0.993 0.434 
## 
##  ================== 
## tBodyAccJerkMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.584 -0.801  0.42   -0.995 0.451 
## 
##  ================== 
## tBodyGyroMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.565 -0.655  0.4    -0.981 0.418 
## 
##  ================== 
## tBodyGyroMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.63  -0.742  0.34   -0.981 0.3   
## 
##  ================== 
## tBodyGyroJerkMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.736 -0.865  0.28   -0.997 0.088 
## 
##  ================== 
## tBodyGyroJerkMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.755 -0.881  0.27   -0.998 0.25  
## 
##  ================== 
## fBodyAcc.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.576 -0.769  0.43   -0.995 0.537 
## 
##  ================== 
## fBodyAcc.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.489 -0.595  0.48   -0.989 0.524 
## 
##  ================== 
## fBodyAcc.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.63  -0.724  0.36   -0.989 0.281 
## 
##  ================== 
## fBodyAcc.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.552 -0.747  0.46   -0.997 0.659 
## 
##  ================== 
## fBodyAcc.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.481 -0.513  0.47   -0.991 0.56  
## 
##  ================== 
## fBodyAcc.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.582 -0.644  0.39   -0.987 0.687 
## 
##  ================== 
## fBodyAccJerk.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.614 -0.813  0.4    -0.995 0.474 
## 
##  ================== 
## fBodyAccJerk.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.588 -0.782  0.41   -0.989 0.277 
## 
##  ================== 
## fBodyAccJerk.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.714 -0.871  0.3    -0.992 0.158 
## 
##  ================== 
## fBodyAccJerk.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.612 -0.825  0.4    -0.995 0.477 
## 
##  ================== 
## fBodyAccJerk.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.571 -0.785  0.43   -0.99  0.35  
## 
##  ================== 
## fBodyAccJerk.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.756 -0.895  0.26   -0.993 -0.006
## 
##  ================== 
## fBodyGyro.mean...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.637 -0.73   0.35   -0.993 0.475 
## 
##  ================== 
## fBodyGyro.mean...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.677 -0.814  0.33   -0.994 0.329 
## 
##  ================== 
## fBodyGyro.mean...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.604 -0.791  0.38   -0.986 0.492 
## 
##  ================== 
## fBodyGyro.std...X 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.711 -0.809  0.27   -0.995 0.197 
## 
##  ================== 
## fBodyGyro.std...Y 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.645 -0.796  0.36   -0.994 0.646 
## 
##  ================== 
## fBodyGyro.std...Z 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.658 -0.822  0.34   -0.987 0.522 
## 
##  ================== 
## fBodyAccMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.537 -0.67   0.45   -0.987 0.587 
## 
##  ================== 
## fBodyAccMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.621 -0.651  0.35   -0.988 0.179 
## 
##  ================== 
## fBodyBodyAccJerkMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.576 -0.794  0.43   -0.994 0.538 
## 
##  ================== 
## fBodyBodyAccJerkMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.599 -0.813  0.41   -0.994 0.316 
## 
##  ================== 
## fBodyBodyGyroMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.667 -0.766  0.32   -0.987 0.204 
## 
##  ================== 
## fBodyBodyGyroMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.672 -0.773  0.29   -0.981 0.237 
## 
##  ================== 
## fBodyBodyGyroJerkMag.mean.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.756 -0.878  0.26   -0.998 0.147 
## 
##  ================== 
## fBodyBodyGyroJerkMag.std.. 	 : 	  
##   obs. mean   median  s.d.   min.   max.  
##   180  -0.772 -0.894  0.25   -0.998 0.288 
## 
##  ==================
```
