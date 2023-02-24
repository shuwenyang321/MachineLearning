# MachineLearning

**Enable Model**


**Part 1: Data Source and Contents**

Use the following path as the data source:
  "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true"
 
The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The target feature 'y' labels [1,0], meaning income '>50K' and '<=50K'.



**Part 2: Finding Optimal Value of a key Ensemble Method Hyperparameter**

For Ensemble Models, one of the key hyper-parameter is number of “estimators”. Find the best value of "estimator", ranging from 1 to 100, by creating line graph. 



**Part 3: Building a Random Forest Model**
Using n_estimator values as [50,100,150,200,250,300,350,400,450,500] and keeping all other hyperparameter values at default builds a random forest model. I use accuracy score and AUC evaluate the random forest model and also answer the following two quetions:

1. Write observations about the Classifier’s behavior with respect to the number of estimators.
2. Is there an optimal value of the estimator within the given range?



**Part 4: Building AdaBoost, Gradient Boost, and XGB**
Repeat the process of part 3 above for AdaBoost, Gradient Boost, and XGB Classifiers.
  
  
  
**Part 5: Tune Decision Tree Performance**
I create a table to display the best value of Accuracy and AUC for four models (Random Forest, AdaBoost, Gradient Boost, XGB) in the previous steps

