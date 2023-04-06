# MachineLearning

**Decision Tree Algorithm**


**Part 1: Data Source and Contents**

Use the following path as the data source:
  "https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true"
 
The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The target feature 'y' labels [1,0], meaning income '>50K' and '<=50K'.



**Part 2: Data Quality Analysis (DQA)**
  • Perform a Data Quality Analysis to find missing values, outliers
  • Display descriptive statistics of each column
  • Perform data cleaning, such as eliminating irrelavant characters in DataFrame and using one-hot coding techniques to transform column values



**Part 3: Build Decision Tree Classifier Models**
Definition: Given a data of attributes together with its classes, a decision tree produces a sequence of rules that can be used to classify the data.

Advantages: Decision Tree is simple to understand and visualise, requires little data preparation, and can handle both numerical and categorical data.

Disadvantages: Decision tree can create complex trees that do not generalize well, anddecision trees can be unstable because small variations in the data might result in a completely different tree being generated.

Steps as following:
  -Separate train and test DataFrame
  -Separate features and labels (target variables)
  -Use “DecisionTreeClassifier” algorithm from scikit learn.



**Part 4: Evaluate Decision Tree Performance**
Calculate and display the following:
  • Confusion Matrix 
  • Accuracy, Precision, Recall, F1 Score
  
  
  
**Part 5: Tune Decision Tree Performance**

Try varying FOUR of the hyperparameters manually,and train / score my model for each set of these hyperparameters.

Four Hyperparameters to vary:
  • Split Criteria – ‘Entropy’ or ‘Gini Impurity’
  • Maximum Features 
  • Minimum Sample Leaf 
  • Maximum Depth 
My goal is to determine the hyper-parameter values for the “best-performing” tree with respect to “accuracy”.

At the end, I check run time while running the best model



**Part 6: Visualize Your Best Decision Tree**


**Part 7: Conclusion : Explain my observations by answering following questions**

  How long was your total run time to train the best model?
  Did you find the BEST TREE?
  Write your observations from the visualization of the best tree
  Will this Tree “overfit”?
  
  
  
**Part 8: Prediction using my best Decision Tree Model**

Make prediction of a “new” individual’s Income Category ( <=50K, or >50K ) with the following information
• Hours Worked per Week = 48
• Occupation Category = Mid - Low
• Marriage Status & Relationships = High
• Capital Gain = Yes
• Race-Sex Group = Mid
• Number of Years of Education = 12
• Education Category = High
• Work Class

Evaluate prediction by calculating “probability score”
