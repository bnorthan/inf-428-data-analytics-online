# Terminology 

## KEY TERMINOLOGY  

* Features  
* Feature Vector  
* Supervised  
* Unsupervised  
* Classification  
* Regression  
* Clustering  

## FEATURE

[Wikipedia](https://en.wikipedia.org/wiki/Feature_(machine_learning)) has a good explanation.  

To summarize a feature is a measurable property used to describe a sample  
* Numerical
  * Weight, age, wins, runs scored
* Binary  
  * Yes/No (1 or 0)
  * Male/Female  
* Enumeration/Categorical  
  * Color, City, Education Level  

For example say we want to categorize people.  We could use height, weight, gender, and education level.  Height and weight would be numerical features, gender a binary feature, and education level a categorical feature.  

## FEATURES VECTOR

* A feature vector is an array of Features, often represented by a row of a dataset.  For example a person.... 

|Age|Gender|Education|  
|---|----|----|
|32	|M	|High School
|27	|F	|PhD  

* To do machine learning we need to convert each feature to a numerical value.  For example     

|Age|Gender|Education|    
|---|----|----|  
|32	|0	|1  
|27	|1	|4   

Feature vectors are a row in a dataset.  

## SUPERVISED VS UNSUPERVISED

[see this link](https://towardsdatascience.com/supervised-vs-unsupervised-learning-14f68e32ea8d) for some background.

* Supervised  
  * Have datapoints (x) and labels (y)
* The labels are usually  
  * Classes (a cateogry, like dog or cat).
  * Numerical values 
* Machine learns relationships between x and y    
* Unsupervised
  * Have datapoints (x) but no labels  

In this class we will focus on supervised learning... that is learning for which we have a training set with the answer.  

## CLASSIFICATION  

[This article](https://medium.com/quick-code/regression-versus-classification-machine-learning-whats-the-difference-345c56dd15f7) talks about the differences between regression and classification.  

Classification is a type of machine learning where we identify "what" something is.   In this case the labels are categories.   

* Identify a target variable
  * Fore examle type of animal (dog, cat)  
  * Credit risk category (high, low)
  * disease state
* Target variable is called a class
* Steps  
  * Train algorithm (give it known examples)
  * Apply to unknown (new) examples  

## REGRESSION  
* Prediction of a numerical value  
* In this case the goal is to learn how to predict numeric outcomes.  
    * For example predicting whether or not an individual will develop diabetes is a classification problem.
    * predicting the value of their blood sugar is a regression problem.  
* Linear regression
  * y: a output
  * x: one or more inputs
  * y=ax, or y=a1*x1+a2*x2+a3*x3  

## CLUSTERING
* No Target Value
* Divide Data Into Groups
* Unsupervised Learning  




