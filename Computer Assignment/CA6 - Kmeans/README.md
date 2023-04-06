# MachineLearning

**Customer Segmentation using K-Means Clustering**


The aim of this assignment is to perform customer segmentation using the K-Means clustering algorithm in order to better understand the different types of customers in a given dataset called 'Mall_Customers." 

There are five columns in this given dataset; that are CustomerID, Gender, Age, Annual Income and spending power. Categorical variables is gender and others are numerical. The target variables for this case are annual income and spending power. 

Part 1: 
Load the dataset and perform exploratory data analysis (EDA): 

1. Import the necessary libraries (pandas, numpy, matplotlib, seaborn) 

2. Load the dataset using pandas and display the first few rows and the shape

3. Check for missing values. The results shows no missing values, so no furthur action needed. 

4. Visualize the distribution of numerical variables of 'age' 'annual income' 'spending score' using histograms. Additionally, use boxplots to visualize 'spending score' for checking outliers 

Part 2:
Data preprocessing for clustering: 

1. create a copy of the original dataframe and encode 'Gender' for dummy variable 

2. feature selection: Choose the appropriate features 'Annual income' and 'Spending score' for clustering within a new DataFrame

3. Perform feature scaling, StandardScaler 

Part 3: 
Implement k-means clustering: 

1. Import the KMeans class from the sklearn.cluster module 

2. Use the Silhouette Method to determine the optimal number of clusters and visualize a silhouette analysis

3. Train the KMeans model with the optimal number of clusters 

4. Obtain the cluster assignments for each data point

5. Create a scatter plot of the selected features, colored by cluster assignment 


Part 4: 
K-means visualization with analysis and recommendation


Cluster 1 (Purple): low spending, low annual income; They are likely to be more price-sensitive and may prioritize essential products or services. Marketing strategies targeting this segment should focus on offering affordable, high-value products and promotions.

Cluster 2 (Blue): low spending, high annual income; This may indicate a more conservative spending behavior or that they prefer to save rather than spend on your platform. To engage this segment, you could focus on showcasing the value and quality of your products or offering personalized recommendations based on their specific interests.

Cluster 3 (Green-Blue): low annual income, high spending power; This could imply that they prioritize spending on your platform, even if it means cutting back on other expenses. To retain and grow this segment, you can offer loyalty programs or exclusive discounts that reward their continued patronage.

Cluster 4 (Green): moderate annual income, moderate spending power; this group may need furthur demographic data for analysis in order to provide suitable strategy

Cluster 5 (Yellow): high annual income, high spending power; They might be more interested in premium or luxury products and services. Targeting this segment could involve offering tailored recommendations, premium services, or exclusive products that cater to their tastes and preferences.
