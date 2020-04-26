# K Nearest Neighbors
 
## References

[Wikipedia](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)  
[Youtube](https://www.youtube.com/watch?v=UqYde-LULfs)
[Scikitlearn](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)  

## K Nearest Neighbors
* Start with a set of example points  
* The goal is to classify new points  
  * For every example point  
* Calculate Geometric Distance to new point  
* Sort distances in decreasing order  
* Take k smallest distances  
* Use majority class as prediction for new point   

## K Nearest Neighbor in KNIME  

On the KNIME Server there is an example in the 'Machine_Learning' folder.  Get the example from the server and open it.  Your KNIME should look as follows.   

<img src="KNIMEKNearest.jpg" width="842">  

The video [here](https://youtu.be/KdGyOyhZ40s) shows how to build the workflow.  

* File Reader  
  * Read the data
* Color Manager and Scatter Plot  
  * Look for patterns and relationships  
*  Partitioning  
  * Divide into Training and Testing  
*  Normalizer (Optional)  
  * Precondition data so every feature has similar weight  
*  K Nearest Neighbor 
  * Inputs are training and testing data  
*  Scorer  
  * Test how the learner performed  

## K Nearest Neighbor in Python 

This [notebook](https://github.com/bnorthan/inf-428-data-analytics-online/blob/master/python/notebooks/machine_learning/DiabetesKNearestNeighbors.ipynb) shows how to run K Nearest Neighbors in Python.  

* Uses scikit learn library
* Steps are the same as KNIME
  * Divide into Training and Testing
  * Train a classifier
  * Apply classifier to test set
  * Score

