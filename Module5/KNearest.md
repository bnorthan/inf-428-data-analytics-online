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

* Uses scikit learn library
* Steps are the same as KNIME
  * Divide into Training and Testing
  * Train a classifier
  * Apply classifier to test set
  * Score

