## CategoricalDataAnalysism_BrownFat
The objective of this analysis is to identify the factors determining the existence and the volume of brown fat in a large cohort of cancer patients. 
We investigate relationship between many explanatory variables and the presence of brown fat and build a model in order to estimate the probability of 
having brown fat.

Data is gathered from Molecular Imaging Center at The University of Sherbrooke. 
Tidyverse, ggplot2 and broom are some examples of libraries used to find the best possible model which predicts the existence of brown 
fat based on multiple GOF tests, Hosmer-Lemeshow test, ROC curve etc. 

Our final model is : BrownFat ~ Sex + Diabetes + Age + Ext_Temp +Two_Day_Temp + Three_Day_Temp + Weight + LBW

This was an academic project in teams of 5. 
