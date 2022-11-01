# abloneMLR

The purpose of this project is to utilize olsrr R package to run variable selection and regression analysis. 

We want to predict the age of abalone from physical measurements by building a multiple regression model. This dataset consists of 4,177 observations and 9 variables: sex, length, diameter, height, whole_weight, shucked_weight, viscera_weight, shell_weight, rings. The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope.

Link is detailed characteristics of each variable according to the data source (https://archive.ics.uci.edu/ml/datasets/abalone)

Name   Data Type   Measurement Unit   Description  
Sex   nominal   --   M, F, and I (infant)  
Length   continuous   mm   Longest shell measurement  
Diameter   continuous   mm   perpendicular to length  
Height   continuous   mm   with meat in shell  
Whole weight   continuous   grams   whole abalone  
Shucked weight   continuous   grams   weight of meat  
Viscera weight   continuous   grams   gut weight (after bleeding)  
Shell weight   continuous   grams   after being dried  
Rings   integer   --   +1.5 gives the age in years
