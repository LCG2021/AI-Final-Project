# Classification on the Telco-Churn Dataset
Classification on the Telco-Churn Dataset The dataset and its description is available at Kaggle. The goal of this task is to analyze the behavior of telecom customers and understand what factors are important to retain customers.


1. Visualize the univariate distribution of each input variable and the target variable “churn”.

2. Split data into training and test sets. Convert each categorical variable into numerical variables using one-hot-encoding. 

Example of one-hot encoding: 

Gender: Male -> (1, 0), Female -> (0, 1) 

Ethnicity: 1. Caucasian, 2. African American, 3. Hispanic, 4. Asian, 5. Native American, 6. Pacific Islander 

One-hot encoded labels: 

         1 → (1, 0, 0, 0, 0, 0)
  
         2 → (0, 1, 0, 0, 0, 0)
   
         6 → (0, 0, 0, 0, 0, 1)
   
3. Evaluate the following classification models: 

   a. Logistic Regression
   
   b. Support Vector Machine 
   
   c. K Nearest Neighbors
   
   d. Decision Trees 
   
   e. Random Forests 

Note that you need to decide the choice of hyper-parameters for the models, such as the value of k for k nearest neighbor method and the maximum depth for the random forest method.

4. Choose the best model by analyzing the accuracy, precision, recall, and F-1 score.

5. Which types of customers are less likely to end the service?
