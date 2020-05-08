
### Assignment

Machine Learning  

Compile all answers in a word document.  For questions that require Python notebooks or KNIME workflows submit a screen shot. 

The data needed for the assignment is [here](https://github.com/bnorthan/inf-428-data-analytics-online/tree/master/python/notebooks/machine_learning)

titanic_preprocessed.csv - it the titanic data with some preprocessing done to deal with missing data.  Use this for the titanic question.  (note more preprocessing may be needed)   

dataingdata.csv - this is the dating data  

1. Explain why we divide data into testing and training sets.     

2. A class takes a test and the entire class does horrible.  The prof gives them a second chance.  The next week   

  a) The prof gives them the exact same test over again, same questions, same answers.  The students do well this time.  Have they really learned anything?  
  b) Alternatively the prof give them a slightly different test on the same material.  Different questions but on the same concepts.  The students do well this time.  Have they learned anything?   

  c) Explain how this anecdote relates to the concept of 'self prediction'   

See [this video](https://www.youtube.com/watch?v=5fxB3XPY0CU) for hints.  

3.  In KNIME what node can be used to divide data into training and testing sets?  

4.  Explain what overfitting is. (the [video](https://www.youtube.com/watch?v=5fxB3XPY0CU) referenced in part 2 may also be useful here)  

5.  Make a scatter plot of some the indian-diabetes data using distinct types of points (for example distinct colors) for each class (use KNIME or Python).  Find two features (columns) that visually do a good job of separating the data - 2 points.  Submit screen shot.   

6.  Describe K-Nearest Neighbor algorithm in words (submit  word doc or e-mail) -1 points  

7.  Perform classification with KNIME k-nearest neighbors and KNIME Naive Bayes algorithm on the dating dataset and titanic dataset remember to divide into training and testing (use the partitioner) - 4 points  

	For the dating dataset “did_she_like” is the class.
		Report accuracy of the algorithm 
	For the titanic dataset “survived” is the class
		Report accuracy of the algorithm 

	For both embed a screenshot of the workflow

8. Perform classification with Scikitlearn k-nearest neighbors  on the dating and titanic dataset, remember to divide into training and testing- 4 points  

9. In class we have sometimes been testing our algorithms on extremely simple datasets.  Datasets so simple that a human can see what the answer is right away.  Why is it useful to test an algorithm on a very simple dataset??  (1 point)   (See python/machineLearning/DiabetesMachineLearning.ipynb)

10.  We have two drinks.  We know they are either Cola or Coffee.   We measure the following features   
Temperature  
% carbonation  

Is this a good design??  When will a classifier based on these features succeed??  When will it fail??   (1 point)

